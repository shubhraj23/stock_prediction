📈 Stock Price Prediction with LSTM, Linear Regression & Random Forest

A complete machine learning and deep learning project to forecast stock closing prices using historical data. This project supports three models:

- ✅ Linear Regression (Baseline ML model)
- 🌲 Random Forest (Ensemble ML model)
- 🧠 LSTM (Deep learning sequence model)

Built using Python, scikit-learn, TensorFlow, and yFinance to make predictions on-demand for any stock symbol (e.g., `AAPL`, `TCS.NS`, `INFY.NS`).

## 🚀 Features

- 📊 Fetches real-time historical stock data using `yfinance`
- 🔍 Feature engineering with lag-based input
- 🔁 Time-aware train-test split (no data leakage)
- 🔥 Deep learning support using LSTM with Keras
- 📉 Performance metrics: RMSE and MAE
- 📈 Visualizations comparing actual vs predicted prices

## 🧠 Models Used

1. Linear Regression
A simple baseline model using the previous day's closing price as the main feature.

2. Random Forest Regressor
A non-linear, tree-based ensemble model with `n_estimators=200` to capture patterns better than LR.

3. LSTM (Long Short-Term Memory)
A deep learning model ideal for time series:
- Uses 60-day rolling window of past prices
- Stacked LSTM layers with dropout to prevent overfitting
- Trained on normalized data using `MinMaxScaler`


