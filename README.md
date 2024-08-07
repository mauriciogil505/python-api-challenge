# python-api-challenge

## WeatherPy Project
This project involves analyzing weather data using the OpenWeather API and Geoapify API to investigate the relationship between various weather parameters and geographical factors. The analysis includes extracting data from the APIs, processing it, and performing linear regression to explore the correlation between weather parameters and latitude. The results are visualized through scatter plots with linear regression lines using Pandas and Matplotlib in a Jupyter Notebook environment.

## Project Overview
The objective of this project is to practice data extraction from APIs, data processing, and linear regression analysis. The project includes the following tasks:

Extract data from the OpenWeather API and Geoapify API.
Transform the data to fit the desired analysis format.
Perform linear regression analysis for different weather parameters.
Visualize the results using scatter plots with linear regression lines.

## Project Data Sources
The project uses the following APIs to gather data:

OpenWeather API: Provides weather data for multiple cities around the world.
Geoapify API: Provides geographical data such as latitude and longitude for various locations.

## Extract, Transform, Analyze Process
### Step 1: Extract Data
Use the OpenWeather API to gather weather data for multiple cities.
Use the Geoapify API to get the geographical coordinates (latitude and longitude) for these cities.
Load the data into Pandas DataFrames for further processing.

### Step 2: Transform Data
Clean and preprocess the data to ensure it is in the desired format.
Split the data into two DataFrames: one for the Northern Hemisphere and one for the Southern Hemisphere.
Extract relevant weather parameters such as temperature, humidity, cloudiness, and wind speed.

### Step 3: Analyze Data
Perform linear regression analysis to identify relationships between weather parameters and latitude.
Generate scatter plots with linear regression lines to visualize the results.

## Linear Regression Analysis
The linear regression analysis involves the following steps:

Define a function to create linear regression plots.
  Generate scatter plots for the following relationships:
  Northern Hemisphere: Temperature vs. Latitude
  Southern Hemisphere: Temperature vs. Latitude
  Northern Hemisphere: Humidity vs. Latitude
  Southern Hemisphere: Humidity vs. Latitude
  Northern Hemisphere: Cloudiness vs. Latitude
  Southern Hemisphere: Cloudiness vs. Latitude
  Northern Hemisphere: Wind Speed vs. Latitude
  Southern Hemisphere: Wind Speed vs. Latitude
Include the linear regression line, the model's formula, and the r^2 values in the plots.

## VacationPy Project
This project involves planning future vacations using weather data and geographical data to identify ideal locations. The analysis includes visualizing weather conditions and locating hotels using the Geoapify API.

### Project Overview
The objective of this project is to identify potential vacation spots based on specific weather criteria and locate nearby hotels. The project includes the following tasks:

Filter cities based on ideal weather conditions.
Use the Geoapify API to find hotels near the selected cities.
Visualize the cities and hotels on a map.

### Project Data Sources
The project uses the following API to gather data:

Geoapify API: Provides geographical data and places information (e.g., hotels).

### Steps
#### Step 1: Filter Cities Based on Ideal Weather Conditions
Load the weather data and geographical coordinates for multiple cities.
Filter cities with ideal weather conditions (e.g., temperature between 15°C and 25°C, humidity less than 20%, wind speed less than 4.5 m/s, and zero cloudiness).
Drop any rows with null values.

#### Step 2: Find Hotels Near Selected Cities
Use the Geoapify API to search for hotels within 10,000 meters of each city's coordinates.
Add the hotel name to the DataFrame.

#### Step 3: Visualize Cities and Hotels on a Map
Use GeoViews and hvplot to create a map that displays a point for every city.
Adjust the size of the points based on humidity.

## Instructions
To run the project, follow these steps:

1. Clone the repository to your local machine.
2. Obtain API keys for the OpenWeather API and Geoapify API and store them securely.
3. Launch the Jupyter notebook files (`WeatherPy.ipynb` and `VacationPy.ipynb`).
4. Import the required dependencies.
5. Extract data using the API keys.
6. Clean and transform the data.
7. Perform linear regression analysis (WeatherPy).
8. Filter cities and find hotels (VacationPy).
9. Generate visualizations to display the results.
10. Verify the results by examining the plots and maps.

## Project Files
WeatherPy.ipynb`: The main analysis code for the WeatherPy project.
VacationPy.ipynb`: The main analysis code for the VacationPy project.
Linear Regression Plots: Generated scatter plots with linear regression lines are saved in the output folder.
Map Visualizations: Generated maps with city and hotel locations.

### Credits
Class Notes
Peer Discussions
XPert Learning Assistant
Study Materials
Stack Overflow
OpenWeather API
Geoapify API

