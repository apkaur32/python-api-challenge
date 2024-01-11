# python-api-challenge
Challenge#6 HW


Instructions
This activity is broken down into two deliverables, WeatherPy and VacationPy.

Part 1: WeatherPy
In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. 
You'll use the citipy Python library, the OpenWeatherMap API, and your problem-solving skills to create a representative model of weather across cities in the WeatherPy.ipynb Jupyter notebook provided.
Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed
Requirement 2: Compute Linear Regression for Each Relationship
Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude)
Then create the following plots:
Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude

Part 2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.
1. Open the VacationPy.ipynb starter code and create a map that displays a point for every city in the city_data_df DataFrame.
2. Narrow down the city_data_df DataFrame to find your ideal weather condition (Feel free to adjust your specifications).
3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
5. Add the hotel name and the country as additional information in the hover message for each city on the map.

Remember to add gitignore file to repo. 
