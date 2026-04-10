# Futures Volatility Forecasting

This project explores volatility forecasting on high-frequency CME futures data using realized-volatility features and a range of benchmark and machine learning models.

## Overview
The notebook builds a forecasting pipeline using intraday 1-minute futures data and compares models including:
- HAR
- HAR-RS
- XGBoost
- Feed-forward neural network

The focus is on rolling train-test evaluation using metrics such as QLIKE and log-R².

## Main file
- `futures_volatility_forecasting.ipynb`

## Note on data
Raw market data is not included in this repository. The project uses futures data sourced via Databento, which has restrictions on redistribution. This repository is intended to show methodology, code structure, and representative results rather than redistribute source data.
