##  Election_Analysis

## Project Overview
In this project, a hypothetical Colorado Board of Elections employee has assigned me to complete an audit of a recent local congressional election. I am tasked with completing the following:

1. Calculate the total number of votes cast.
2. Get a complete list of the candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on the popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.1, Visual Studio code 1.61.2

## Summary
My analysis produced the following information:
- There were 369,711 votes cast in the election.
- The candidates receiving votes and their corresponding vote counts and percentage of total votes were as follows:
  -  Charles Casper Stockham: 23% (85,213 votes)
  -  Diana DeGette: 73.8% (272,892 votes)
  -  Raymon Anthony Doane: 3.1% (11,606)
- The winner of the election was Diana DeGette  

## Audit Overview
The audit for this project included a request for a further breakdown of the votes based by county and the following:
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

## Audit Summary
Additionaly analysis by county produced the following insights:
- The county with the highest turnout was Denver
- The breakdown of votes by county and percentage of total vote count:
  - Jefferson County with 38,855 votes (10.5% of total votes)
  - Denver County with 306,055 votes (82.8% of total votes)
  - Arapahoe County with 24,801 votes (6.7% of total votes)

## Election Audit Summary
This script provides a template that can be used for future elections. Some examples of how this can be done include:
 1. The code itself can be modified to include other counties for statewide election using the same code and an expanded data set listing more counties
![County Code](https://github.com/FinTechNOLA/Election_Analysis/blob/main/CountyVoteCountCode.png)
 2. The breakdown of the data can reflect percentages to a greater degree of precision by simply changing the decimal point in the data summary code.
![Results Code](https://github.com/FinTechNOLA/Election_Analysis/blob/main/CountyResults.png)

