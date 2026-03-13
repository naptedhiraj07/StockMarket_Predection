# 📈 AAPL Stock Price Prediction (2020-2025)
"This project uses Linear Regression to predict the next day's closing price of a stock based on its historical performance fetched via the Yahoo Finance API."

## Tools Used:
 - Yfinance
 - Pandas
 - Numpy
 - Scikit-learn
 - Matplotlib

## 📖 Project Overview:
This project focuses on leveraging historical data to predict the future price movements of Apple Inc. (AAPL).
Utilizing a comprehensive 5-year dataset spanning from January 1, 2020, to January 1, 2025, the project implements machine learning techniques—specifically Long Short-Term Memory (LSTM) neural networks and Linear Regression—to analyze temporal dependencies and forecast closing prices. 

 ## 🚀 Key Steps in Pipeline:
Data Acquisition: Loading AAPL historical data.
Preprocessing: Handling missing values, normalizing data using MinMaxScaler, and structuring data for time-series forecasting.
Feature Engineering: Creating lag features (e.g., 7-day moving average).
Model Training: Training LSTM for deep learning or Linear Regression for baseline comparisons.
Evaluation: Measuring performance using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).





