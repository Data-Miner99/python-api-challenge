# python-api-challenge

1. Create a new repository for this project called python-api-challenge. Do not add this homework to an existing repository.

2. Clone the new repository to your computer.

3. Inside your local Git repository, create a directory for this assignment. Use a folder name that corresponds to the Challenges, such as WeatherPy.

4. Inside the folder you just created, add the files called api_keys.py, WeatherPy.ipynb, and VacationPy.ipynb that you will find in the starter code ZIP file provided. These will be the main scripts to run for each analysis.

5. Before you push your changes to GitHub, add a .gitignore file.

## WeatherPy
Create a Python script to visualize the weather of over 500 cities of varying distances from the equator.
Use the OpenWeatherMap API to retrieve weather data from the cities list generated. create a series of scatter plots to showcase the following relationships:
* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

Compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).
Create a series of scatter plots. Include the linear regression line, the model's formula, and the r values.

You should create the following plots:
* Northern Hemisphere: Temperature vs. Latitude
* Southern Hemisphere: Temperature vs. Latitude
* Northern Hemisphere: Humidity vs. Latitude
* Southern Hemisphere: Humidity vs. Latitude
* Northern Hemisphere: Cloudiness vs. Latitude
* Southern Hemisphere: Cloudiness vs. Latitude
* Northern Hemisphere: Wind Speed vs. Latitude
* Southern Hemisphere: Wind Speed vs. Latitude

## VacationPy
Use your weather data skills to plan future vacations.
Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.
1. Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.
2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

    * A max temperature lower than 27 degrees but higher than 21
    * Wind speed less than 4.5 m/s
    * Zero cloudiness
3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
5. Add the hotel name and the country as additional information in the hover message for each city on the map.