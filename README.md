# World_Weather_Analysis

## **Overview of Project**

The purpose of the project is to retireve and analyze weather data using OpenWeatherMap API for 2000 random latitudes and logitudes of citiies.
Dataframes are used to view and organize weather data and randomly pick travel destination routes that can be mapped using Geoapify API and geoviews libraries 



##  Weather Data

- An API call was made to retireve data that shows max temperatures, city, country, humiditiy and current weather description for 2000 citiies. 
Random latitudes and longitudes were chosen as input to determine the cities analyzed for weather conditions. The data was extracted into a dataframe and exported to an excel spreadsheet.

### Travel Destinations Map

- A sample data was selected based on max and min temperatures to perform further analysis on the city weather file. A call to the geoapify to retrieve 
hotel data for the cities selected by matching lng and lat to the nearest hotel. The information was placed on a map using goeviews to visualize the locations and create points where hotel information, city
and temperatures can be viewed by clicking and hovering over the map points.

	![alt text](https://github.com/mabulhassan/Pewlett-Hackard-Analysis/blob/main/WeatherPy_vacation_map.png "vacation map")

###Travel Itinerary Map

- An itinerary is created based on four lat and long points that are on the same route. The points are matched with cities using geoapify and a map visual is created to view the travel route.

	![alt text](https://github.com/mabulhassan/Pewlett-Hackard-Analysis/blob/main/WeatherPy_travel_map.png "travel map")

	
## Summary

- The weather analysis data uses open api to map locations based on latitude and longitude points with map visuals. 
The generated json format data includes details on city, country, weather and temperatue data that can assist in travel decisions
The mpa visualization provides a user friendly UI that provides an easy to undersand travel routes.
## Resources


**Software:** PostgreSQL 11, pgAdmin 4, geoviews, geoapify, openweather api. 
