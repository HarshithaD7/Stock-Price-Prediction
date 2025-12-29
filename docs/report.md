# Stock Price Prediction Using LSTM  
## Detailed Project Report

---

## 1. Introduction
Stock price prediction is a challenging problem due to market volatility and temporal dependencies.  
This project applies a **Long Short-Term Memory (LSTM)** neural network to forecast stock closing prices using historical data.

---

## 2. Problem Statement
The objective is to predict future stock closing prices based on past price movements using a deep learning time-series model.

---

## 3. Dataset Description
- Dataset: All Stocks 5-Year Dataset
- Total records: 619,040
- Company selected for modeling: Apple Inc. (AAPL)
- Time range analyzed: 2013–2018

---

## 4. Data Preprocessing
- Converted date column to datetime format
- Filtered data for Apple stock
- Scaled closing prices using MinMaxScaler
- Created sequences of 60 time steps
- Split data into training and testing sets (95% training)

---

## 5. Model Architecture
- Two stacked LSTM layers with 64 units each
- Dense layer with 32 neurons
- Dropout layer with rate 0.5
- Final dense output layer
- Optimizer: Adam
- Loss: Mean Squared Error

---

## 6. Training Process
- Model trained for 10 epochs
- Training loss reduced from 0.0490 to 0.0060
- Indicates effective learning and convergence

---

## 7. Evaluation Results
- Mean Squared Error (MSE): 187.00
- Root Mean Squared Error (RMSE): 13.67

These results indicate that the model predictions closely follow actual stock prices.

---

## 8. Visualization and Results
- Training data represents historical prices
- Test data is used for evaluation
- Predicted values closely align with actual closing prices
- Visualization confirms trend-following behavior

---

## 9. Observations
- LSTM captures temporal dependencies effectively
- Prediction accuracy decreases during volatile periods
- Overall trend prediction is strong

---

## 10. Conclusion
This project demonstrates the effectiveness of LSTM networks for stock price prediction.  
The model successfully learns historical patterns and generates reliable forecasts.

---

## 11. Future Improvements
- Incorporate technical indicators
- Use multivariate inputs
- Experiment with deeper LSTM architectures
- Apply attention mechanisms
- Include macroeconomic indicators

---

## 12. References
- TensorFlow Documentation
- Keras LSTM Guide
- Time-Series Forecasting Literature
