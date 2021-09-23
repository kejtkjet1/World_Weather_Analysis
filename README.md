# World_Weather_Analysis

Travel app created using OpenWeather and Google Maps API

## Overview of Project

### Purpose

We aimed to create a list of vacation recommendations based on a random list of 2000 latitudes and longitudes, with focus on finding locations with the weather conditions, most specifically the max and min temperature within the preferred range. The list was used to create an itinerary of a trip between the US and Canada. 

## Travel recommendation - step by step

- Initial step: Creating the Weather Database
    - Created a random list of latitudes and longitudes. 
    - The list was converted to cities using citipy
    -  We used Open Weather API to gather information on the weather in all of those locations
    - We mapped those locations with Google maps via the API
    - The list was saved in a dataframe which was exported to CSV File located below:

https://github.com/kejtkjet1/World_Weather_Analysis/tree/main/Weather_database

- Second Step: Vacation Search
    - We looked at various weather conditions to find locations from our initial database that matched the preferred weather descriptions of the user
    - Using Google Places API - we identified hotels in the desired locations and removed any locations without a hotel from our database
    - Using Google Maps API - we mapped out all the locations that matched out weather condition search criteria

![WeatherPy_vacation_map.png](https://github.com/kejtkjet1/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

- All the Vacation search steps are included in the code below:

https://github.com/kejtkjet1/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb

- Final Step: Creating the Itinerary
    - We looked at all the locations identified in the initial steps and picked 4 cities to trave to
    - Using Google Directions API - we mapped out a route for our trip

![WeatherPy_travel_map.png](https://github.com/kejtkjet1/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

    - We also created a map that identifies all the hotels we want to visit as with information including the city and current weather conditions

![WeatherPy_travel_map.png](https://github.com/kejtkjet1/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

The code for the itinerary can be found below

https://github.com/kejtkjet1/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb


## Summary

- This was the first week we started workign with API and seeing the applications as well as the power of Python and Pandas and Jupyter Notebook coming together. With just minimal programming knowledge we were able to create an interactive experiece that pulled data from numerous data sources and created a very basic application.  