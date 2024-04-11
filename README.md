# python-api-challenge

This challenge includes two components:

## **City Weather Analysis** <br>
The aim of the weather analysis is to visualize the weather of over 500 cities of varying distances from the equator. Using the citipy Python library, the script finds the nearest cities to a random list of Latitude and Longitude pairs, and then uses the OpenWeatherMap API to collect weather data on these cities. Scatter plots are then created to showcase the following relationships: Latitude vs. Temperature; Latitude vs. Humidity; Latitude vs. Cloudiness; and Latitude vs. Wind Speed. A function is then defined to compute the linear regression for each of these relationships, with separate scatter plots then being created using the function for each of these relationships in both the Northern Hemisphere and Southern Hemisphere. The correlation values are also shown and a basic analysis for each relationship is provided.


## **Vacation Hotels** <br>
The aim of the Vacation Hotels component is to write a scipt to visualize available hotels to plan future vacations. Using the geoViews Python library and the Geoapify API, the scipt first imports the csv file of cities created in the previous Weather exercise, and then plots all the cities on the world map. Cities are then filtered by a specific weather condition to narrow down the ideal location for a vacation. Using the Geoapify API, the script then searches for hotels within a particular distance from the Latitude and Longitude of each city and collects these into a new DataFrame. A final map is created to show the locations of the available hotel for each desired city.


### **References** <br>
This project uses the [Open Weather Map API](https://openweathermap.org/api) and the [Geoapify API](https://www.geoapify.com/).
