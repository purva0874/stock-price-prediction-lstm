# Stock Price Prediction using LSTM

This project uses a Long Short-Term Memory (LSTM) neural network to predict the next day's closing price of RELIANCE.NS stock based on the past 60 days of data.

## Overview
- Data collected via `yfinance` (2015–2024)
- Model input: 60-day closing price window
- Model output: 1-day future price
- MAE: ₹17.32 (approx. 0.7% error)
- Forecasts and evaluation done using Keras LSTM

##  Tech Stack
- Python
- pandas, numpy, matplotlib
- scikit-learn (scaling, metrics)
- yfinance (data)
- TensorFlow/Keras (model)

## Results
The model tracks trends well with a low average error and visually aligns with real stock movement.

![Plot of actual vs predicted prices](#)

## Example Prediction
```python
Predicted next-day closing price: ₹2437.59
