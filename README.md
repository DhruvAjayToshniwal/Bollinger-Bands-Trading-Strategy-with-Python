# Bollinger Bands Trading Strategy with Python

This Python script demonstrates a simple trading strategy using Bollinger Bands. The script fetches historical data for a given stock symbol, calculates Bollinger Bands along with several other technical indicators, and visualizes the data and the trading signals generated. It also compares this strategy to a simple 'Buy and Hold' strategy for S&P 500.

## Requirements

The script uses the following Python libraries:

- pandas
- yfinance
- matplotlib

You can install these libraries using pip:
pip install pandas yfinance matplotlib

## Usage

Just run the script using Python:
python bollinger_bands.py


Replace `'GOOGL'` in the script with the ticker symbol of the stock you want to analyze.

## Code Overview

The script performs the following steps:

1. Fetches historical data for the specified stock symbol using the Yahoo Finance API (via the yfinance library).
2. Calculates Bollinger Bands, Simple Moving Averages (SMA), Exponential Moving Averages (EMA), Moving Average Convergence Divergence (MACD), and Relative Strength Index (RSI).
3. Visualizes the calculated data and trading signals.
4. Implements a trading strategy based on Bollinger Bands: buys 100 shares when the closing price is below the lower Bollinger Band, and sells all shares when the closing price is above the upper Bollinger Band.
5. Compares this strategy to a simple 'Buy and Hold' strategy for S&P 500 by calculating and plotting the portfolio growth for both strategies.
