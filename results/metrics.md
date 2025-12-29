# Model Evaluation Metrics  
## Stock Price Prediction Using LSTM

This document presents the quantitative performance metrics obtained from the trained LSTM model.

---

## Dataset Details
- Company analyzed: **Apple Inc. (AAPL)**
- Training data size: **1,197 records**
- Testing data: Remaining records after training split
- Feature used: Closing price

---

## Model Configuration
- Model type: LSTM Neural Network
- Input sequence length: 60
- LSTM layers: 2
- Hidden units: 64
- Dropout rate: 0.5
- Output layer: 1 neuron
- Optimizer: Adam
- Loss function: Mean Squared Error

---

## Training Loss (Epoch-wise)

| Epoch | Loss |
|------:|------:|
| 1 | 0.0490 |
| 2 | 0.0107 |
| 3 | 0.0074 |
| 4 | 0.0084 |
| 5 | 0.0082 |
| 6 | 0.0068 |
| 7 | 0.0070 |
| 8 | 0.0064 |
| 9 | 0.0059 |
| 10 | 0.0060 |

---

## Test Set Evaluation

- **Mean Squared Error (MSE):** `187.00450202984752`
- **Root Mean Squared Error (RMSE):** `13.67495894070061`

---

## Summary
The decreasing training loss indicates stable learning and convergence.  
The RMSE value suggests that the model predictions are reasonably close to actual stock prices on unseen data.
