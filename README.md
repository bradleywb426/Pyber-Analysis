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

How does the following vary by city type:

- total rides
- total drivers
- total fares
-  avg fare per ride
-  avgfare per driver

Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

## Summary

Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

----------------------

## Results

Based on the analysis of the election audit:

- A ***total of 369,711 votes*** were cast in this district for this congressional election.
  - This was determined by simply adding each new vote to a total vote variable
  - <img src=https://github.com/bradleywb426/election-analysis/blob/main/Resources/code_2.png width="300">

- The breakdown of votes by county was:
  - ***Jefferson county*** casted ***38,855 votes***, which was ***10.5% of the total votes***.
  - ***Denver county*** casted ***306,055 votes***, which was ***82.8% of the total votes***.
  - ***Arapahoe county*** casted ***24,801 votes***, which was ***6.7% of the total votes***.
   - The breakdown of votes by county was determined using a nested for loop that would go through every row of data and add a county to a list of counties if it was not already present, and then add any votes cast in said county to a county total
   - The percentage was then calculated by dividing the votes per county by the total votes for the election
   - <img src=https://github.com/bradleywb426/election-analysis/blob/main/Resources/code_1.png width="400">

- ***Denver county*** had the ***largest voter turnout*** out of all counties, with 306,055 total votes.
  - The largest voter turnout was determined by checking the turnout with a given county against largest turnout variables, and updated the variable to match the checked county if the checked county has a larger turnout
  - <img src=https://github.com/bradleywb426/election-analysis/blob/main/Resources/code_3.png width="400">

- The breakdown of votes by candidates was:
  - ***Charles Casper Stockham*** won ***85,213 votes***, which was ***23.0% of the total votes***.
  - ***Diana DeGette*** won ***272,892 votes***, which was ***73.8% of the total votes***.
  - ***Raymon Anthony Doane*** won ***11,606 votes***, which was ***3.1% of the total votes***.
  - The breakdown of votes by candidates was determined using a nested for loop that went through every row of data and would add any unique candidate names to a list, and then add any votes cast for the candidate to their respective totals; while the percentages were calculated by dividing each candidates votes by the total votes
  - <img src=https://github.com/bradleywb426/election-analysis/blob/main/Resources/code_4.png width="450">

- The ***winner of the elections was Diana DeGette***, who received ***272,892 votes*** or ***73.8% of the total votes***.
  - The winner of the election was determined by checking a candidates vote count and percentage against the current winning count and percentage, and updating the winning stats if a candidate has a higher vote count and percentage
  - <img src=https://github.com/bradleywb426/election-analysis/blob/main/Resources/code_5.png width="600">

## Summary

This Python script delivered quick and accurate results of this Colorado District election, and is capable of delivering these results in a presentable manner in a seperate file. However, this is not the only election this script can work for, as it would only need some general modifications to make this script more applicable to any election. 

- An easy place to start is creating functions for this script, as several parts of the code are very similar and could be re-written to be a function that takes a variable or two and produces the desired results. 

  - For example, a function could be created to find the vote counts and vote percentages for candidates, counties, and more.
   
- Another area of improvement could be streamlining the printing of all results into one block of code at the end, instead of periodic updates throughout the script.
