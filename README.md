## python-api-challenge

# WeatherPy
First part of the WeatherPy notebook, the OpenWeatherMap API is used to retrieve weather data for the cities generated in the starter code. Four scatter plots are then created to showcase the relationships between latitude and different weather parameters: temperature, humidity, cloudiness, and wind speed. The scatter plots visually demonstrate how these weather parameters vary with latitude and provide insights into the patterns and correlations between latitude and weather conditions.

Second part of the WeatherPy notebook, linear regression analysis is performed for each relationship between latitude and weather parameters. The scatter plots are separated into the Northern Hemisphere and the Southern Hemisphere. A function is defined to create the linear regression plots, which includes calculating the regression line, slope, intercept, r-value (correlation coefficient), p-value, and standard error of the regression. By creating a series of scatter plots with linear regression lines, the analysis provides a clear visualization of the relationships between latitude and temperature, humidity, cloudiness, and wind speed. The plots help identify any trends or correlations between latitude and these weather parameters in both the Northern and Southern Hemispheres.

# VacationPy
In the VacationPy.ipynb notebook, a map will be created using the city_data_df DataFrame. Each city in the DataFrame will be represented by a point on the map, with the size of the point indicating the humidity level of the city.

The city_data_df DataFrame will be narrowed down to find cities that match specific weather conditions, such as a maximum temperature between 21 and 27 degrees, wind speed less than 4.5 m/s, and zero cloudiness.

A new DataFrame called hotel_df will be created to store the city, country, coordinates, and humidity. The Geoapify API will be used to find the first hotel located within 10,000 meters of each city's coordinates. The hotel name and country information will be added to the hover message for each city on the map.
