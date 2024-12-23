# Sales-Forecasting-model
Build a LSTM model for sales forecasting while analyzing the impact of weather conditions on Sales.

# AIM
Fetch data from SQL server hosted to Python.

Analyze the influence of weather on burger sales.

# Tech Stack
Language: Python

Libraries: pandas, numpy, tensorflow, pymysql, matplotlib, sklearn, keras, lightgbm

# Approach
Loading Data:

Using pymysql library to fetch data from the MySQL server.
Exploratory Data Analysis:

Plotting date vs sales graph based on regions.
Autocorrelation and partial correlation plot.
Plotting average, maximum, and minimum of features.
Scatterplot and histograms of the features.
Data Preprocessing:

Windowing the Data:
Train-Validation Split:
Data Rescaling using QuantileTransformer:
Building Baseline Model (lightgbm) and Feature Importance:
Building LSTM Model:

Predictions for One Day into Future:
