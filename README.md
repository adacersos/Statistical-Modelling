# Statistical-Modelling

# London Weather Forecasting

## Project Overview

This school project, conducted from Nov 2023 to Dec 2023, focused on forecasting the weather in London using time series modeling techniques.

## Data Source

Utilized London weather data obtained from Kaggle, stored as a CSV file, to create a comprehensive time series model.

## Data Preprocessing

- Imported the dataset and addressed missing values by filling them with the next available data point.
- Conducted exploratory data analysis to identify influencing factors on temperature predictions. Concluded that the historical temperature data captured all the factors such as sunlight and global radiation so it was not necessary to include these factors in the model.
- Handled outliers to ensure model robustness.

## Time Series Modeling

Developed various models including:
- Linear Regression
- Seasonal Regression
- ARIMA Model

## Model Selection

After rigorous evaluation, the seasonal model emerged as the ideal choice due to its superior performance on test data and resistance to overfitting.

## Visualization

- Visualized future temperatures, incorporating 68% and 95% confidence interval spreads.
- Demonstrated the range of possible temperature values for enhanced interpretability.

## Project Status

This project was conducted as part of a school assignment and is considered complete.

Feel free to explore the notebooks and visualizations to gain insights into the London weather forecasting process!

## Getting Started 

1. downlaod this file [London Weather Forecasting.ipynb](https://github.com/adacersos/Statistical-Modelling/blob/main/London%20Weather%20Forecasting.ipynb)
2. Raw data is here https://github.com/adacersos/Statistical-Modelling/blob/main/london_weather.csv


# Case 1: Stock Price Forecaster

- **Timeline:** January 2024 - February 2024
- **Creator:** Adam Cersosimo

## Overview

This project involves creating an Exponential Smoothing State Space Model (ETS) to predict future stock prices for selected companies based on historical stock price data.

## Key Steps

1. **Data Acquisition and Cleaning**
   - Downloaded 5 years of stock data for Google, Boeing, Netflix, Chipotle, and Tesla from yahoo finance
   - Loaded each dataset into Jupyter Notebooks using Pandas and removed unnecessary columns
   - Isolated the adjusted stock closing price to use in the time series model

2. **Model Development:**
   - Split the Data into training and test sets to create ETS and linear models to see how they perform on test data
   - Implemented the ETS model to predict the next year of stock price for each stock
4. **Results:**
   - Despite the inherent challenges in predicting stock prices accurately, the model demonstrated an ability to identify the general direction of stock price movements
   - MSE was substantially higher for certain stocks which could be attributed to randomness or a higher volatility in the stock

## Getting Started 

1. downlaod this file https://github.com/adacersos/Statistical-Modelling/blob/main/Stock%20Price%20Predictor.ipynb
2. Raw data is here [https://github.com/adacersos/Statistical-Modelling/blob/main/london_weather.csv](https://github.com/adacersos/Statistical-Modelling/tree/main/stock%20csv%20folder)
