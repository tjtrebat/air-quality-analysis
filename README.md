# air-quality-analysis
# Overview
This project focuses on predicting air quality measurements based on various meteorological factors using linear regression models. The dataset includes information on average temperature, pressure, wind, humidity, and different air quality pollutants such as PM10, CO, NO2, O3, PM25, and SO2.

# Code Structure
Data Loading:

The project starts by loading the dataset from the CSV file.
# Linear Regression Models:

Separate linear regression models are built for different weather predictors (avg_temperature, avg_pressure, avg_wind, avg_humidity) and their impact on air quality pollutants.
The models are trained and evaluated using metrics like Mean Squared Error (MSE), R-squared, and Adjusted R-squared.
# Model Evaluation:

Each model's performance is assessed individually, considering its ability to predict air quality pollutants based on the chosen predictor.
Comparative Analysis:

A comparative analysis is performed across different models, considering factors like MSE, R-squared, and Adjusted R-squared to determine the overall effectiveness.
Recommendations:

Recommendations for further improvement, such as exploring alternative models, conducting feature engineering, and assessing the impact of outliers, are provided.
Usage
# Requirements:

Make sure to install the required libraries by running pip install -r requirements.txt.
Run the Code:

Execute the Python script or Jupyter notebook to run the linear regression models.
Interpret Results:

Review the outputs, including coefficients, MSE, and R-squared values, to understand the predictive power of each model.
Comparative Analysis:

Analyze the comparative results to identify which weather predictors are more effective in predicting specific air quality pollutants.
