# 📈 Stock Market Analysis and Prediction using LSTM

## 📌 Project Overview

This project focuses on stock market data analysis and price prediction using Python and Long Short-Term Memory (LSTM), a type of Recurrent Neural Network (RNN).

The project analyzes historical stock data from Apple, Google, Microsoft, and Amazon. It uses an LSTM deep learning model to predict Apple's future stock price trends based on historical closing prices.

## 🎯 Objectives

- Analyze historical stock market data.
- Compare stock closing prices and trading volumes.
- Calculate daily returns and moving averages.
- Visualize stock trends and correlations.
- Analyze the relationship between risk and expected returns.
- Build an LSTM model to predict stock price trends.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Yahoo Finance (yfinance)
- Scikit-learn
- TensorFlow / Keras

## 📊 Stock Market Analysis

The project analyzes four technology companies:

- Apple (AAPL)
- Google (GOOG)
- Microsoft (MSFT)
- Amazon (AMZN)

The analysis includes:

- Historical closing price visualization.
- Trading volume analysis.
- 10-day, 20-day, and 50-day moving averages.
- Daily percentage returns.
- Stock return distributions.
- Correlation analysis.
- Risk and expected return comparison.

## 🧠 LSTM Model Development

An LSTM neural network is developed to predict Apple's stock closing prices.

**Model architecture:**
- First LSTM layer: 128 units.
- Second LSTM layer: 64 units.
- Dense layer: 25 units.
- Output layer: 1 unit.

**Model configuration:**
- Optimizer: Adam
- Loss function: Mean Squared Error (MSE)
- Lookback period: 60 days
- Training split: 80%
- Training epochs: 10
- Batch size: 32

## ⚙️ Project Workflow

1. Download historical stock data using Yahoo Finance.
2. Perform data cleaning and exploratory data analysis.
3. Calculate moving averages and daily returns.
4. Visualize stock trends and correlations.
5. Prepare Apple's closing price data.
6. Normalize data using MinMaxScaler.
7. Create 60-day sequences for LSTM training.
8. Train and evaluate the LSTM model.
9. Compare actual and predicted stock prices.

## 📈 Results

The project generates visual comparisons between actual and predicted Apple stock prices and calculates Root Mean Squared Error (RMSE) to evaluate prediction performance.

## 📦 Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn yfinance scikit-learn tensorflow
```

## 🚀 Run the Project

```bash
python stock_market_analysis_prediction_using_lstm.py
```

## 👨‍💻 Author

**Krishnasurya**

M.Sc. Business Statistics Graduate

Skills: Python | Machine Learning | Deep Learning | Data Analytics

GitHub: https://github.com/krishsurya
