# World_Weather_Analysis

## Overview 
The task was to collect and analyze weather data across cities worldwide. I used the data to recomend ideal hotels based on the clients weather preferences. I created a Pandas DataFrame with 500 or more of the world's unique cities and the weather data in real time. 

## Resources
* Software: Python, jupyter-notebook
* Data Source: WeatherPy_Database.csv; WeatherPy_vacation.csv
* Souce Code: Weather_Database; Vacation_Search; Vacation_Itinerary
* APIs: openWeatherWeather API (https://openweathermap.org/api); Google Maps APIs

## Results
* Weather_DataBase Folder:
  * Generated a set of random latitudes and longitudes 
  * Retrieve nearest city
  * Perform an API call 
  * Retrieve current weather data with weather descriptions in each city
  * Create new DataFrame containing the updated weather data and print to csv file

[WeatherPy_Database.csv](https://github.com/nataliepoorcreations/World_Weather_Analysis/files/9163864/WeatherPy_Database.csv)


* Vacation_Search Folder:
  * Retrieve customer weather preferences with input statements
  * Use preferences to identify potential travel destinations and nearby hotels
  * Show destinations on a marker layer map with pop-up markers

Weather Vacation Map


![WeatherPy_vacation_map](https://user-images.githubusercontent.com/106033535/180612637-6068858f-073a-4da7-a5a0-64806328bab8.png)


* Vacation_Itinerary Folder: 
  * Create a travel itinerary that shows the route between four cities based on client's possible travel destinations usint the Google Directions API
  * Create a marker map with pop-up markers for each city on itinerary

Weather Travel Map Itinerary


![WeatherPy_travel_map](https://user-images.githubusercontent.com/106033535/180612630-727732de-37c1-49e6-ac19-f016afb5bd88.png)


Weather Travel Map with Markers


![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/106033535/180612625-330940a6-4b57-4151-ab25-f6429adf0ce4.png)

