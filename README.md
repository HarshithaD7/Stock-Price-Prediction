# Stock Price Prediction Using LSTM

## Project Description
This project implements a **time-series stock price prediction system** using a **Long Short-Term Memory (LSTM)** neural network.  
The model is trained on **five years of historical stock price data** and evaluated using Apple Inc. (AAPL) stock prices.

The implementation is developed and executed entirely in a **Kaggle Notebook environment** using TensorFlow and Keras.

---

## Objectives
- Load and preprocess multi-company stock market data
- Perform exploratory data analysis on major technology stocks
- Build an LSTM-based deep learning model for time-series forecasting
- Predict future stock closing prices
- Evaluate prediction performance using error metrics

---

## Dataset
- Dataset: **All Stocks 5-Year Dataset**
- Total records: **619,040**
- Features include:
  - Date
  - Open
  - High
  - Low
  - Close
  - Volume
  - Company symbol

For modeling, **Apple (AAPL)** stock data between **2013 and 2018** is used.

---

## Model Used
- Deep Learning Model: **LSTM (Long Short-Term Memory)**
- Framework: TensorFlow / Keras
- Sequence length: **60 time steps**
- Optimizer: Adam
- Loss function: Mean Squared Error (MSE)
- Training epochs: **10**

---

## Results Overview
- **Mean Squared Error (MSE):** 187.00
- **Root Mean Squared Error (RMSE):** 13.67

Detailed evaluation metrics and analysis are available in:
- `results/metrics.md`
- `results/observations.md`

---

## Source Code
The complete implementation is provided as a Jupyter Notebook in the `src/` folder.

---

