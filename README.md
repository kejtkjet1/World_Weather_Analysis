# World_Weather_Analysis

Travel app creative using Weather and Google Maps API

## Overview of Project

### Purpose

We aimed to create a list of vacation recommendations based on a random list of 2000 latitudes and longitudes, with focus on finding locations with the weather conditions, most specifically the max and min temperature within the preferred range. The list was used to create an itinerary of a trip between the US and Canada. 

## Travel recommendation - step by step

- Initial step, create a random list of latitudes and longitudes. 

- Results by county
    - Jefferson: 10.5% (38,855)
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801)

- The county which received the largest nubmer of votes: Denver 306,055

- Results by candidate
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)

- Election Winner: Diana DeGette with 73.8% of the votes

The summary of the results can be seen on the image below: 


![electionsummary.png](https://github.com/kejtkjet1/election-analysis/blob/main/resources/electionsummary.png)

The CSV file we used to analize the results: https://github.com/kejtkjet1/election-analysis/blob/main/resources/election_results.csv

The Txt file with the results summary can be located under: https://github.com/kejtkjet1/election-analysis/blob/main/analysis/election_results.txt

## Summary

- This Python Script is very versatile, it can be used to perform elecion audits for other elections. Few possible modifications to make it more versatile
    - We could add additional variables if the csv captured demographics of the voting public we could perform similar analysis by demographic breakouts
    - Alternatively we could look to perform an analysis of winning candidates per election district 