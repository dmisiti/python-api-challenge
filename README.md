Module 6 Challenge -- APIs

In this challenge, Python scripting was used to visualize the weather of over 500 cities of varying distances from the equator. 

First, the OpenWeatherMap API was used to retrieve weather data. Analysis was done using this data to showcase the relationship between:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

Linear regression analysis was also performed using the generated scatter plots for each of these four relationships, for both northern and southern hemisphere data.

Second, the Geoapify API and the geoViews Python library were used to create map visualizations, showing the location of all cities on the map, and then narrowing down the cities to those with ideal weather conditions. These cities were mapped along with hotel information for the specified city.

This repository contains one primary folder called WeatherPy. This folder contains:
- the WeatherPy Jupyter Notebook file (containing the analysis for the first part of this challenge)
- the VacationPy Jupyter Notebook file (containing the analysis for the second part of this challenge)
- an output_data folder (containing the first four scatter plots generated in part one, as well as the output cities data spreadsheet generated from part one)
