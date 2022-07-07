# An Analysis of Pyber Ride Data

Analysing Data from Pyber rides to uncover trends based on the types of city: Rural, Suburban, and Urban

## Resources

- Data:
  - city_data.csv
  - ride_data.csv
- Software: Python 3.10.5

## Overview

V. Isualize has tasked us with analyzing the relationship between city types and how Pyber usage differs amongst the city types. First, we had to create and provide a Dataframe for our analysis, and then make a line plot illustrating the differences.

## Results

The first aspect of our Pyber Analysis involved creating a DataFrame of Pyber data (Total Rides, Total Drivers, Total Fares, Average Fare per Ride, Average Fare per Driver) grouped by different city types (Rural, Suburban, and Urban). The DataFrame is listed below, and contains the data discussed below.

<img src="https://github.com/bradleywb426/Pyber-Analysis/blob/main/analysis/challenge_df.png" width=500>

### Total Rides

  There are a total of 125 rides in Rural-type cities, which is the smallest total number of rides of all city types. Suburban cities have 625 rides total, which is 5 times as many rides as in Rural-type cities. Urban-type cities have a total of 1,625 rides, which is 13 times as many rides in Rural-type cities and 2.6 times as many rides as Suburban-type cities. Therefore, Urban-type cities have the most total rides. 

### Total Drivers

  In Rural-type cities, there are a total of 78 drivers, which is the smallest number of drivers of all city types. For Suburban-type cities, there are a total of 490 drivers, which is about 6.3 times as many drivers as Rural-type cities. Urban cities have a a total of 2,405 drivers, which is about 30.8 times as many drivers as Rural-type cities and about 4.9 times as many drivers as Suburban-type cities. Therefore, Urban-type cities have the largest total number of drivers.

### Total Fares

  Rural cities have the lowest total fares, with a total of $4,327.93 in total fares. In Suburban-type cities, the total fare is $19,356.33, which is around 4.5 times greater than total fares in Rural cities. Urban-type cities have a total of $39,854.38 in fares, which is about 2.1 times the total fares for Suburban cities and about 9.2 times the total fares of Rural cities. Therefore, Urban-type cities have the largest total fares.

### Total Fares (Monthly)

The total fares for each city type can also be observed as monthly totals for each city type till the end of April, as seen in the line plot below. From the plot, it can be seen that total fares in Urban cities are always the greatest, total fares in Suburban cities are always less than Urban and greater than Rural, and Rural cities always have the smallest monthly totals. It can also be seen that the monthly total fares by city type exist in distinct bands, meaning that there is no overlap between the minimums and maximums of monthly totals by city type. Rural cities appear to have relatively consistent total monthly fares, while Suburban cities appear to have maximums and minimums over the course of around 4 weeks. Urban cities appear to dip in the colder winter months, and slowly increase as it approaches summer.

<img src="https://github.com/bradleywb426/Pyber-Analysis/blob/main/analysis/Pyber_fare_summary.png" width=700>

### Average Fare per Ride

Urban-type cities have $24.53 average fare per ride, which is the lowest average fare per ride out of all city types. For Suburban cities, the average fare per ride is $30.97, which is about 1.26 times the average fare for Urban cities. Rural cities have an average fare of $34.62 per ride, which is about 1.41 times the average fare per ride in Urban cities and about 1.12 times the average fare per ride for Suburban cities. Therefore, Rural-type cities have the greatest average fare per ride out of all city types.

### Average Fare per Driver

Urban cities have an average fare per driver of $16.57, which is the lowest average fare per driver.

  - U: $16.57
  - S: $39.50
  - R: $55.49

## Summary

Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

----------------------

## Summary

This Python script delivered quick and accurate results of this Colorado District election, and is capable of delivering these results in a presentable manner in a seperate file. However, this is not the only election this script can work for, as it would only need some general modifications to make this script more applicable to any election. 

- An easy place to start is creating functions for this script, as several parts of the code are very similar and could be re-written to be a function that takes a variable or two and produces the desired results. 

  - For example, a function could be created to find the vote counts and vote percentages for candidates, counties, and more.
   
- Another area of improvement could be streamlining the printing of all results into one block of code at the end, instead of periodic updates throughout the script.
