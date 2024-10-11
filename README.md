# Python API Challenge: WeatherPy and VacationPy

## Python API Challenge

This assignment explores the relationship between weather variables and latitude using Python, specifically leveraging APIs and data visualization techniques. The project is divided into two main parts: **WeatherPy** and **VacationPy**.

### Objective

The primary objective is to analyze weather data from various cities around the world to understand how temperature, humidity, cloudiness, and wind speed vary with latitude, particularly as we approach the equator. Additionally, the assignment includes using this weather data to plan ideal vacation spots based on favorable conditions.

## Project Structure

1. **Part 1: WeatherPy**
   - **Data Retrieval**: Use the OpenWeatherMap API to gather weather data for over 500 cities based on their geographic coordinates.
   - **Data Visualization**: Create scatter plots to illustrate the relationships between latitude and various weather variables:
     - Latitude vs. Temperature
     - Latitude vs. Humidity
     - Latitude vs. Cloudiness
     - Latitude vs. Wind Speed
   - **Linear Regression**: Compute and visualize linear regression for each relationship, separating analyses for the Northern and Southern Hemispheres.

2. **Part 2: VacationPy**
   - **Map Visualization**: Create a map displaying cities based on humidity levels.
   - **Filtering Ideal Conditions**: Narrow down the dataset to find cities that meet specific weather criteria (e.g., ideal temperature range, low wind speed, no cloudiness).
   - **Hotel Search**: Use the Geoapify API to locate hotels within a specified distance from the ideal cities, providing additional information in the visualization.

### Key Requirements

- Retrieve weather data from the OpenWeatherMap API.
- Create scatter plots for each weather variable against latitude.
- Compute and display linear regression for these relationships.
- Visualize cities on a map, with points sized by humidity.
- Filter cities based on specific weather conditions and find nearby hotels.

## Conclusion

This assignment combines API usage, data analysis, and visualization techniques to gain insights into weather patterns and aid in vacation planning. By completing this project, you will enhance your skills in working with external data sources and creating meaningful visual representations of complex datasets.
