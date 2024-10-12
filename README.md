# Stock_Price_Prediction

# Stock Price Prediction using ARIMA Model

This project demonstrates how to use the ARIMA (AutoRegressive Integrated Moving Average) model to forecast stock prices. The dataset consists of historical daily stock prices for ITC Ltd, spanning from **January 1, 2024** to **September 20, 2024**.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [ARIMA Model](#arima-model)
- [Usage](#usage)


## Project Overview
The goal of this project is to predict future stock prices based on historical data using the ARIMA model, a popular statistical method for time series forecasting. 

## Dataset

The dataset contains the following columns:

- **Date**: The date of the stock prices.
- **Open**: The opening price of the stock.
- **High**: The highest price of the day.
- **Low**: The lowest price of the day.
- **Close**: The closing price of the stock.
- **Volume**: The total number of shares traded on the given day.

This data provides the foundation for time series analysis and prediction using the ARIMA model.

## ARIMA Model

The ARIMA model is used for analyzing and forecasting time series data by:
- **Auto-regressive (AR)**: Refers to the dependency between an observation and a number of lagged observations.
- **Integrated (I)**: Refers to the differencing of raw observations to make the time series stationary.
- **Moving Average (MA)**: Refers to the dependency between an observation and a residual error from a moving average model applied to lagged observations.

This model helps in making predictions for future stock prices based on historical trends.

## Usage

To run the stock price prediction model, follow these steps:
1. Upload the stock price dataset.
2. Choose the ARIMA model parameters (p, d, q).
3. Visualize the predicted stock prices.

