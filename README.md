# Stock-Prediction-using-LSTM

## Problem Statement
The accuracy of stock price prediction is impacted by multiple factors, including market volatility, economic indicators, and historical price trends.

## Proposed Solution

### Data Preprocessing:
1. **Data Normalization**
    - All historical stock prices were normalized to ensure consistency and to improve the performance of the LSTM model.
2. **Sequence Creation**
    - Created sequences of 60 past data points to serve as input for predicting the next stock price.

### Algorithm Implementation:
1. **Long Short-Term Memory (LSTM) Network**
    - Implemented an LSTM network to model the temporal dependencies in the stock price data.
    - The model architecture includes stacked LSTM layers with dropout for regularization and a dense layer for the final prediction.

### Results
- **Mean Absolute Error (MAE)**: 0.02
- **Mean Squared Error (MSE)**: 0.001
- **Root Mean Squared Error (RMSE)**: 0.031
- **R² Score**: 0.95