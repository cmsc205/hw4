Homework 4
================
Put Your Names Here
Due Friday, February 3 by 11:59 p.m.

Instructions
------------

Complete this assignment in this .Rmd, knit it and upload it to your github repository for homework 4 (which will be created once I know what the groups are). When you upload your files, make sure that you include **all** of the files that are generated (hw4.md, and the hw4\_files folder, assuming that you did not rename the hw4.Rmd file).

Data
----

All domestic flights leaving George Bush Intercontinental Airport (IAH) in Houston in 2011. There are 5 data sets to consider:

-   `flights` \[227,496 x 14\]: Flight data.
-   `weather` \[8,723 x 14\]: Hourly weather data.
-   `planes` \[2,853 x 9\]: Plane metadata.
-   `airports` \[3,376 x 7\]: Airport metadata.
-   `states` \[48 x 3\]: (Lower 48) state data.

I have embeded a code chunk that loads the data, but won't print to your knitted .md file since I set `echo=FALSE` in the chunk options.

------------------------------------------------------------------------

Question 1:
-----------

Plot a "time series" of the proportion of flights that were delayed by &gt; 30 minutes on each day. i.e.

-   the x-axis should be some notion of time
-   the y-axis should be the proportion.

Using this plot, indicate describe the [seasonality](https://en.wikipedia.org/wiki/Seasonality) of when delays over 30 minutes tend to occur.

------------------------------------------------------------------------

Question 2:
-----------

Some people prefer flying on older planes. Even though they aren't as nice, they tend to have more room. Which airlines should these people favor?

------------------------------------------------------------------------

Question 3:
-----------

-   What states did Southwest Airlines' **flight paths** tend to fly to?
-   What states did Southwest Airlines' **flights** tend to fly to?

For example, Southwest Airlines Flight 60 to Dallas consists of a single flight path, but since it flew 299 times in 2013, it would be counted as 299 flights.

------------------------------------------------------------------------

Question 4:
-----------

I want to know proportionately what regions (NE, south, west, midwest) each carrier flies to/from Houston in the month of July. Consider the `month()` function from the `lubridate` package.
