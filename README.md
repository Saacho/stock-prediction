
# Stock Price Predictor

## Overview
This project implements a Long Short-Term Memory (LSTM) neural network to predict stock prices, specifically using Apple (AAPL) historical data. The model is trained on OHLCV data, scaled, and transformed into sequences to forecast the next closing price.

## Features
- Data fetching using yfinance
- Data preprocessing with scaling and sequence generation
- LSTM model implemented in PyTorch
- Training on GPU (if available)
- Visualization of actual vs. predicted stock prices
- Error analysis with RMSE metrics

## Requirements
- Python 3.8+
- numpy, pandas, matplotlib, yfinance
- scikit-learn
- torch (PyTorch)
- jupyter (if using notebooks)

## Usage
1. Clone the repository.
2. Install dependencies with `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python script to train and evaluate the model.

## Results
- Achieved a test RMSE of approximately 8.13 on AAPL stock data.
- Visualization highlights model performance and prediction trends.

## License
This project is for educational purposes only and does not constitute financial advice.
