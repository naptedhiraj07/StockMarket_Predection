# Stock Price Prediction using ML

This project utilizes a **Long Short-Term Memory (LSTM)** recurrent neural network to predict the closing stock price of Google (Alphabet Inc.) based on historical data.

## 🚀 Overview
The model uses the past **60 days** of stock prices to predict the price of the next day. It leverages the `yfinance` API for real-time data collection and `TensorFlow/Keras` for building the deep learning architecture.

## 📊 Project Structure
* **Data Sourcing:** Historical data (2015-2023) fetched via Yahoo Finance.
* **Preprocessing:** Data is scaled using `MinMaxScaler` and reshaped for LSTM compatibility.
* **Model Architecture:**
    * 2 LSTM layers (50 units each) with Dropout layers (0.2) to prevent overfitting.
    * 1 Dense output layer to predict the final price.
* **Evaluation:** The model is tested on 2024 data and visualized using Matplotlib.

## 🛠️ Requirements
To run this project, you need the following Python libraries:
```bash
pip install numpy pandas matplotlib yfinance scikit-learn tensorflow

