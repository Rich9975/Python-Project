# Crypto Price Analysis Project – Richmond Dias

This project addresses a data analyst task focused on retrieving, cleaning, and visualizing historical price data for Ethereum and Bitcoin using Python.

## Project Overview

Using `yfinance`, `pandas`, and `matplotlib`, this project:

- Downloads 1 month of 2-minute interval data for ETH and BTC
- Cleans and preprocesses the data (handling nulls, outliers, invalid OHLC values)
- Identifies the most volatile trading day for each coin
- Plots:
  - Intraday price time-series chart
  - Daily candlestick (OHLC) charts
  - Simple Moving Averages (SMAs) to demonstrate trends and effects of lookback period

##  Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `yfinance`
- `datetime`

## Output

The Jupyter notebook includes:

- Data cleaning functions and documentation
- Side-by-side analysis of Bitcoin and Ethereum
- Visualizations for:
  - Intraday volatility
  - Candlestick charts with SMAs
- Bonus: Parameter tuning for SMA periods

##  How to Run

1. Install required packages:
   ```bash
   pip install yfinance pandas matplotlib

