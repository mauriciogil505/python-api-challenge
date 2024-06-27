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
Extract, Transform, Analyze Process
- Step 1: Extract Data
Use the OpenWeather API to gather weather data for multiple cities.
Use the Geoapify API to get the geographical coordinates (latitude and longitude) for these cities.
Load the data into Pandas DataFrames for further processing.
- Step 2: Transform Data
Clean and preprocess the data to ensure it is in the desired format.
Split the data into two DataFrames: one for the Northern Hemisphere and one for the Southern Hemisphere.
Extract relevant weather parameters such as temperature, humidity, cloudiness, and wind speed.
- Step 3: Analyze Data
Perform linear regression analysis to identify relationships between weather parameters and latitude.
Generate scatter plots with linear regression lines to visualize the results.
Linear Regression Analysis
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

## Instructions
To run the project, follow these steps:

Clone the repository to your local machine.
Obtain API keys for the OpenWeather API and Geoapify API and store them securely.
Launch the Jupyter notebook file.
Import the required dependencies.
Extract data using the API keys.
Clean and transform the data.
Perform linear regression analysis.
Generate scatter plots to visualize the results.
Verify the results by examining the scatter plots and linear regression statistics.

The project requires the following Python libraries:

pandas
numpy
matplotlib
scipy
requests
jupyter

## Project Files
Jupyter Notebook: The main analysis code is located in the WeatherPy.ipynb file.
Linear Regression Plots: Generated scatter plots with linear regression lines are saved in the output folder.

### Credits
Class Notes
Peer Discussions
XPert Learning Assistant
Study Materials
Stack Overflow
OpenWeather API
Geoapify API
