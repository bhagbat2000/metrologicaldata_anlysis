# metrologicaldata_anlysis

Our goal is to transform the raw data into information and then convert that information into knowledge.
We will be performing some basic tasks to perform our analysis such as
-Data cleaning
-Data normalizing
-Testing the hypothesis

The Null Hypothesis H0 is “Has the Apparent temperature and humidity compared monthly across 10 years of the data indicate an increase due to Global warming”
  The H0means we need to find whether the average Apparent temperature for the month of a month say April starting from 2006 to 2016 and the average humidity for the same period have increased or not. This monthly analysis has to be done for all 12 months over the 10 year period. So you are basically resampling your data from hourly to monthly, then comparing the same month over the 10 year period.
##The first thing we’ll need to do is load in the libraries and dataset we’ll be using.
The first thing to do when you get a new dataset takes a look at some of it. This lets you see that it all read incorrectly and gives an idea of what’s going on with the data. In this case, let’s see if there are any missing values, which will be represented with NaN or None.

Focus on Important factors and exclude others. Here we need Apparent Temperature ( C ), Humidity & Formatted Date so we can resample our data.
Let’s plot the graph for our data using Matplotlib function plot().

