# Market-Beating Portfolio Generator 
Contributors: Umer C, Prithvi S, David Z

A Python-based quantitative investment strategy that constructs and evaluates a 15-stck portfolio using technical indicators with the goal of outperforming the market.

## Project Overview
This project designs a portfolio using historical price data and technical analysis, incorporating portfolio constraints to maintain diversification across holdings. Stocks are scored, standardized, and ranked to identify candidates with strong momentum and trend characteristics.

## Objective
- Build a systematic stock-selection strategy
- Apply technical indicators, such as RSI, Momentum, etc. to rank equities
- Construct a concentrated portfolio aimed at beating the market benchmark

## Methodology
- Pulled historical stock price data from Yahoo Finance
- Evaluated stocks using multiple technical indicators (e.g., momentum, moving averages, and volatility)
- Standardized indicator scores using z-scores and exponential scaling
- Ranked stocks and selected the top 15 for the portfolio
- Generated random weights for technical indicators and simulated portfolio performance
- Selected indicator weights that maximized the portfolio Sharpe ratio


## Technologies Used
- Python
- pandas, numpy
- yfinance
- datetime, math
- Jupyter Notebook

## Results
- Generated a ranked list of stocks based on composite technical scores aligned with the goal of beating the market


