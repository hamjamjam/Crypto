# Crypto
Warren Fulton, John Palmer, Jamie Voros

# Analysis of patterns in major Crypto-currencies

## Data Acquisition

## Backesting
We backtested a series of pairs trades.

Backtesting was written in a Jupyter notebook available in this repo (BackTesting.ipynb).

The backtest implements the pairs trading algorithm with window function and runs on existing data from each asset pair. The backtest runs between dates for which both assets have data. We are using simply the closing price for each trading day (days with no trading are skipped).
