# Gold Price Prediction Using Machine Learning

![gold price](https://resize.indiatvnews.com/en/resize/newbucket/1200_-/2021/01/goldprice-1610094551.jpg)


## Overview

This project aims to predict the price of gold (EUR/USD) using machine learning techniques. Historical data on gold prices and related economic indicators are analyzed to develop a predictive model. This README provides an overview of the project, its purpose, and the steps taken to achieve the goal.

## Dataset

The dataset used in this project is a CSV file containing 2290 rows and 7 columns. The columns include:
- Date
- S&P 500 Index (SPX)
- Gold Price (GLD)
- United States Oil Fund (USO)
- Silver Price (SLV)
- Euro to US Dollar Exchange Rate (EUR/USD)

## Data Preprocessing

### Checking Missing Values
There are no missing values in the dataset, ensuring data quality.

### Summary Statistics
Descriptive statistics of the dataset are as follows:
- Mean gold price: 122.73 EUR/USD
- Minimum gold price: 70 EUR/USD
- Maximum gold price: 184.59 EUR/USD

### Data Analysis

Various data analysis and visualization techniques were applied to understand the relationships between different economic indicators and the gold price.

## Machine Learning Model

### Data Splitting
The dataset was split into training and test sets, with 75% of the data used for training and 25% for testing.

### Random Forest Regression
A Random Forest regression model with 50 estimators and a maximum depth of 3 was used to predict the gold price.

### Model Evaluation
The model was evaluated using the following metrics:
- R-squared (R2) Score: 0.9841
- Adjusted R-squared Score: 0.9841
- Mean Squared Error (MSE): 0.000292
- Mean Absolute Error (MAE): 0.0140
- Mean Absolute Percentage Error (MAPE): 0.0108
- Root Mean Squared Error (RMSE): 0.0171

## Conclusion

The project successfully developed a machine learning model to predict the gold price (EUR/USD) with high accuracy. This model can be used for forecasting gold prices based on economic indicators.

