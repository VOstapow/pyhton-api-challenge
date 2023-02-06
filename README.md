# Python API Challenge

## Background

Data's true power is its ability to definitively answer questions. 
This project allowed me to practice Python requests, APIs, and JSON traversals to answer a fundamental question: 
"What is the weather like as we approach the equator?"

## Part 1: WeatherPy

### Plots to Showcase the Relationship Between Weather Variables and Latitude 

* Used the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code 
* Scatter plot to showcase the relationship between Latitude vs. Temperature 
* Scatter plot to showcase the relationship between Latitude vs. Humidity 
* Scatter plot to showcase the relationship between Latitude vs. Cloudiness 
* Scatter plot to showcase the relationship between Latitude vs. Wind Speed

### Compute Linear Regression for Each Relationship

* Linear regression scatter plot for Northern Hemisphere: Temperature (°C) vs. Latitude 
* Linear regression scatter plot for Southern Hemisphere: Temperature (°C) vs. Latitude 
* Linear regression scatter plot for Northern Hemisphere: Humidity (%) vs. Latitude 
* Linear regression scatter plot for Southern Hemisphere: Humidity (%) vs. Latitude 
* Linear regression scatter plot for Northern Hemisphere: Cloudiness (%) vs. Latitude 
* Linear regression scatter plot for Southern Hemisphere: Cloudiness (%) vs. Latitude 
* Linear regression scatter plot for Northern Hemisphere: Wind Speed (m/s) vs. Latitude 
* Linear regression scatter plot for Southern Hemisphere: Wind Speed (m/s) vs. Latitude 

## Part 2: VacationPy

* Created a map that displays a point for every city in the city_data_df DataFrame
* Narrowed down the city_data_df DataFrame to find my ideal weather condition
* For each city in the hotel_df DataFrame, used the Geoapify API to find the first hotel located within 10,000 metres of the city's coordinates
* Added the hotel name and the country as additional information in the hover message for each city in the map.

