eatherPy and VacationPy

Part 1: WeatherPy

Overview
In this project, we utilized Python, Jupyter notebooks, and various libraries to analyze weather data from over 500 cities. The goal was to create visualizations that showcase the relationship between different weather variables and latitude, followed by computing linear regression for each relationship. The WeatherPy.ipynb Jupyter notebook guided us through the process.

Requirements

Create Plots to Showcase the Relationship Between Weather Variables and Latitude:

Utilized the OpenWeatherMap API to retrieve weather data for cities.
Developed scatter plots to represent the relationships: Latitude vs. Temperature, Latitude vs. Humidity, Latitude vs. Cloudiness, and Latitude vs. Wind Speed.
Compute Linear Regression for Each Relationship:

Calculated linear regression for each relationship.
Separated plots into Northern Hemisphere (≥ 0 degrees latitude) and Southern Hemisphere (< 0 degrees latitude).
Created scatter plots with linear regression lines, model formulas, and r values.
Findings

Noted relationships between latitude and weather variables.
Analyzed linear regression models for each plot.
Part 2: VacationPy

Overview
In the second part of the project, we planned future vacations using weather data, Jupyter notebooks, the GeoViews Python library, and the Geoapify API.

Tasks

Create a Map with City Points:

Displayed points for every city in the city_data_df DataFrame on a map.
Sized points based on humidity.
Narrow Down Ideal Weather Conditions:

Filtered city_data_df for ideal weather conditions: Max temperature between 21 and 27 degrees, wind speed less than 4.5 m/s, and zero cloudiness.
Find Hotels Using Geoapify API:

Created a new DataFrame (hotel_df) to store city, country, coordinates, and humidity.
Used the Geoapify API to find the first hotel within 10,000 meters for each city.
Map Hotels and Cities:

Added hotel names and countries as hover information for each city on the map.
Conclusion
Through WeatherPy and VacationPy, we successfully analyzed and visualized weather data, showcasing relationships and planning ideal vacations based on specific weather conditions. The project demonstrated the use of Python, Jupyter notebooks, APIs, and libraries for data analysis and visualization.
