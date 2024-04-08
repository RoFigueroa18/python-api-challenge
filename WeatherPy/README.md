# python-api-challenge

WeatherPy
In this exercise, we utilized the OpenWeatherMap API to retrieve weather data for a list of cities based on their latitude and longitude coordinates. 
We then created scatter plots to visualize the relationships between latitude and various weather parameters, including temperature, humidity, cloudiness, and wind speed. 
Additionally, we performed linear regression analysis separately for the Northern and Southern Hemispheres to examine any potential correlations between latitude and these weather parameters. The linear regression plots allowed us to assess the strength and direction of these relationships. 
Through this exercise, we aimed to explore how weather parameters vary with latitude, providing insights into regional climatic patterns and potential predictive relationships between latitude and weather conditions. The exercise also involved data manipulation using Pandas DataFrames, visualization using Matplotlib, and statistical analysis using SciPy's linregress function. 
Overall, this exercise provided a practical application of data retrieval, analysis, and visualization techniques to understand geographical patterns of weather parameters and their potential associations with latitude.

VacationPy
We loaded the CSV file containing city data into a Pandas DataFrame.
Imported necessary libraries and configured the environment.
Utilized GeoViews library to create a map displaying points for every city.
Each point's size represents the humidity in that city.
Narrowed down the DataFrame to find cities with ideal weather conditions.
Criteria included a max temperature between 21 and 27 degrees Celsius, wind speed less than 4.5 m/s, and zero cloudiness.
Created a new DataFrame named hotel_df to store city, country, coordinates, humidity, and hotel name.
Set up parameters and made API requests to Geoapify to find the nearest hotel within a specified radius (10,000 meters) for each city.
Added the found hotel names to the hotel_df DataFrame.
Configured the map plot to display hover information for each city's point.
Hover information includes city name, country, humidity, and hotel name.
By following these steps, we were able to visualize cities on a map, filter them based on ideal weather conditions, find nearest hotels for each city using an API, and display additional information interactively through hover tooltips on the map. This process helps in planning vacations by exploring cities with favorable weather conditions and nearby accommodation options.