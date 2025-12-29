# Observations and Analysis  
## Stock Price Prediction Using LSTM

---

## Data Observations
- Stock price data shows clear temporal trends and volatility
- Apple stock exhibits long-term upward movement with short-term fluctuations
- Closing price is suitable for time-series forecasting

---

## Model Behavior
- Training loss decreases significantly within the first few epochs
- The model converges quickly, indicating effective learning of price patterns
- Predictions follow the general trend of actual stock prices

---

## Prediction Analysis
- The LSTM model captures long-term dependencies in stock price movements
- Predicted values closely align with actual prices during stable periods
- Slight deviations occur during rapid price changes, which is common in financial time-series models

---

## Strengths
- Effectively models sequential dependencies
- Handles non-linear temporal relationships
- Suitable for financial time-series forecasting

---

## Limitations
- Sensitive to sudden market fluctuations
- Uses only historical prices, without external factors
- Performance depends on sequence length and hyperparameters

---

## Key Insight
LSTM networks are well-suited for stock price prediction tasks due to their ability to retain historical context over long sequences.
