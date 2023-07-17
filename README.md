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

## Graphs

- ![image](https://github.com/DhruvAjayToshniwal/Bollinger-Bands-Trading-Strategy-with-Python/assets/57616258/f57947b5-ab98-4043-bf87-7b0f8ca41770)
- ![image](https://github.com/DhruvAjayToshniwal/Bollinger-Bands-Trading-Strategy-with-Python/assets/57616258/9cbee70e-9f4f-4b42-a814-81ddae57d9fc)
- ![image](https://github.com/DhruvAjayToshniwal/Bollinger-Bands-Trading-Strategy-with-Python/assets/57616258/5fe357a9-d39d-4223-9ab7-4d695e6cff67)
- ![image](https://github.com/DhruvAjayToshniwal/Bollinger-Bands-Trading-Strategy-with-Python/assets/57616258/57247d6b-c60e-43f8-80df-0518a005df0e)
- ![image](https://github.com/DhruvAjayToshniwal/Bollinger-Bands-Trading-Strategy-with-Python/assets/57616258/4ea0eaee-677a-4f5f-98bf-8993e5b8e5d2)
- ![image](https://github.com/DhruvAjayToshniwal/Bollinger-Bands-Trading-Strategy-with-Python/assets/57616258/c2663c48-5a1a-46ac-a4cc-7cfb879b9d2c)
