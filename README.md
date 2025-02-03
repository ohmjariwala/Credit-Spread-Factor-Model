# Credit Spread Factor Model

This project implements a statistical factor model for predicting credit spreads using the Merton model and market data. The model uses probability of default as a key factor to predict credit spreads for various companies.

## Features

- Calculates Distance to Default using the Merton model
- Computes Probability of Default using market and balance sheet data
- Builds a one-factor model to predict credit spreads
- Includes data validation and error handling
- Provides visualization of model results

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- yfinance
- matplotlib
- scipy

## Usage

The model processes Excel files containing bond data and combines it with market data from yfinance to predict credit spreads. The main components are:

1. Distance to Default calculation
2. Probability of Default computation
3. Factor model building and evaluation
4. Results visualization

## Model Performance

The model evaluates performance using:
- Mean Squared Error (MSE)
- R-squared (R²)
- Residual analysis
- Actual vs Predicted plots

## License

MIT License 