===========================================================
📈 STOCK PRICE PREDICTION: RANDOM FOREST
===========================================================

DESCRIPTION:
This Python script uses machine learning to predict the next day's 
closing price for Tesla (TSLA) using historical market data.

FEATURES:
- Automated Data Retrieval: Fetches real-time stock data via yfinance.
- Feature Engineering: Prepares Open, High, Low, and Volume metrics.
- Predictive Modeling: Implements a Random Forest Regressor for forecasting.
- Performance Evaluation: Calculates Mean Squared Error (MSE) for accuracy.
- Visual Analysis: Generates time-series plots comparing actual vs. predicted prices.

PREREQUISITES:
1. Python 3.8 or higher.
2. Required Libraries: yfinance, pandas, matplotlib, scikit-learn.

INSTALLATION:
Install the required libraries using pip:
   pip install yfinance pandas matplotlib scikit-learn

SETUP:
1. Ensure you have an active internet connection to download ticker data.
2. The script is configured for 'TSLA', but the 'ticker' variable can be 
   modified for any valid Yahoo Finance symbol (e.g., 'AAPL', 'BTC-USD').

HOW TO RUN:
- Script: Run 'python stock_prediction.py' in your terminal.
- Output: The console will print the model's MSE, followed by a trend graph.



⚠️ FINANCIAL DISCLAIMER:
This script is for educational purposes only. Machine learning models 
in finance are subject to high volatility and should not be used as 
the sole basis for real-world trading or investment decisions.

===========================================================
Created for Stock Market Machine Learning Task
===========================================================
