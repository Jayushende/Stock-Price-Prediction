# Stock-Price-Prediction
This project implements a Stock Price Prediction System that analyzes historical stock data, predicts future closing prices, and simulates trading strategies based on those predictions.


# Stock Price Prediction System using Machine Learning

A Python-based **Stock Price Prediction System** that predicts stock closing prices and simulates basic trading strategies using **historical market data**.  
This project demonstrates the power of **Machine Learning**, **Financial Data Analysis**, and **Algorithmic Trading Simulation**.

---

##  Overview

The system:
- Fetches real-time **S&P 500 tickers** from Wikipedia  
- Downloads **15 years of historical stock data** using the Yahoo Finance API  
- Builds **technical indicators** like Simple Moving Averages (SMA) and MACD  
- Trains a **Linear Regression** model to predict daily closing prices  
- Evaluates predictions using **MAE**, **RMSE**, and **R² Score**  
- Simulates a simple **Algorithmic Trading Strategy** and compares it with a traditional buy-and-hold approach

---

## Features

 **Automated Data Collection**  
Fetches the latest list of S&P 500 companies from Wikipedia and retrieves market data using `yfinance`.

 **Feature Engineering**  
Generates technical analysis features such as:
- Previous Close and Volume  
- 5, 10, 20, 50, 100, and 200-day SMAs  
- MACD (Moving Average Convergence Divergence)  
- Day-of-week encoding for trading pattern detection

**Machine Learning Model**  
Trains a **Linear Regression** model using `scikit-learn` to predict future stock closing prices.

 **Evaluation Metrics**  
Cculates:
- **MAE (Mean Absolute Error)**  
- **RMSE (Root Mean Square Error)**  
- **R² Score (Coefficient of Determination)**

 **Trading Simulation**  
Includes a trading backtest:
- Starts with an initial balance ($1000)  
- “Buys” when predicted next-day increase exceeds a threshold  
- Compares **Algorithmic Trading** vs **Simple Hold Strategy**

 **Visualization**  
- Actual vs Predicted Price Plot  
- Trading Performance Graph (account value over time)

- 
## Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| **Programming Language** | Python 3.10+ |
| **Data Handling** | pandas, numpy |
| **Visualization** | matplotlib,
