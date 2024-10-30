# Stock-Markey-Prediction
# Stock Market Prediction using Machine Learning

## Project Overview

This project focuses on predicting stock market movements using historical S&P 500 data. It leverages machine learning techniques, specifically the RandomForestClassifier, along with technical indicators like RSI, MACD, and Bollinger Bands to make predictions. The project evaluates performance using precision, recall, and F1 scores for both training and testing datasets.

## Data Source

The stock market data is sourced from Yahoo Finance using the `yfinance` library. The S&P 500 index (`^GSPC`) is used for historical stock prices.

## Technical Indicators Used

- **Relative Strength Index (RSI)**: Measures the speed and change of price movements.
- **MACD (Moving Average Convergence Divergence)**: A trend-following momentum indicator that shows the relationship between two moving averages.
- **Bollinger Bands**: Used to measure market volatility.

## Model

The model used for prediction is a **RandomForestClassifier** from the `sklearn.ensemble` module. The following steps are performed:

1. Load and preprocess historical data.
2. Add technical indicators (RSI, MACD, Bollinger Bands).
3. Train the RandomForestClassifier using historical stock data.
4. Backtest the model over different time horizons.
5. Evaluate the model's performance using precision, recall, and F1 scores.

## Features Used for Prediction

- Close
- Volume
- Open
- High
- Low
- RSI (Relative Strength Index)
- MACD (Moving Average Convergence Divergence)
- Signal Line (Part of MACD)
- Bollinger Bands (Upper and Lower Bands)

## Evaluation Metrics

- **Precision**: Measures the accuracy of the positive predictions.
- **Recall**: Measures the model's ability to capture actual positives.
- **F1 Score**: The harmonic mean of precision and recall, providing a balance between the two.

## Results

After training the model, the following performance metrics were calculated:

- **Precision** (Test Set): [Insert value]
- **Recall** (Test Set): [Insert value]
- **F1 Score** (Test Set): [Insert value]

- **Precision** (Train Set): [Insert value]
- **Recall** (Train Set): [Insert value]
- **F1 Score** (Train Set): [Insert value]

## Confusion Matrix

Confusion matrices for both training and test data were generated to analyze the model's performance in more detail.

## Visualizations

1. **Train Set: Actual vs Predictions**
2. **Test Set: Actual vs Predictions**
3. **Confusion Matrix** for both training and test datasets

## How to Run the Project

1. Clone the repository:
git clone https://github.com/theshahjee/Stock-Markey-Prediction.git


2. Install the required libraries:
