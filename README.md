# Technical Analysis Dashboard

Streamlit-based interactive dashboard for exploring stock price data and applying common technical indicators.

## Overview

This application allows users to analyze historical stock data for S&P 500 companies using interactive visualizations and technical indicators.

## Features

- Select any S&P 500 stock via live Wikipedia scraping
- Fetch historical price data using Yahoo Finance API
- Interactive candlestick chart visualization
- Technical indicators:
  - Simple Moving Average (SMA)
  - Bollinger Bands
  - Relative Strength Index (RSI)
- Volume overlay support
- Adjustable indicator parameters in real time
- Export filtered dataset as CSV

## Tech Stack

- Python
- Streamlit
- yFinance
- Plotly / Cufflinks
- Pandas

## How it works

1. User selects ticker and date range
2. Data is fetched from Yahoo Finance
3. Indicators are computed dynamically
4. Interactive Plotly chart is rendered in Streamlit

## Notes

This project is intended for educational and analytical exploration of financial time series data. It is not a trading system.