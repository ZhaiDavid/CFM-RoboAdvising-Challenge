# Market-Beating Portfolio Generator 
Contributors: Umer C, Prithvi S, David Z

A Python-based quantitative investment strategy that constructs and evaluates a 15-stck portfolio using technical indicators with the goal of outperforming the market.

## Project Overview
This project designs a portfolio using historical price data and technical analysis, incorporating portfolio constraints to maintain diversification across holdings. Stocks are scored, standardized, and ranked to identify candidates with strong momentum and trend characteristics.

## Objective
- Build a systematic stock-selection strategy
- Apply technical indicators to rank equities
- Construct a concentrated portfolio aimed at beating the market benchmark

## Methodology
- Pulled historical stock price data using Yahoo Finance
- Evaluated stocks using multiple technical indicators (e.g., momentum and trend signals)
- Standardized indicator scores using z-scores and exponential scaling
- Ranked stocks and selected the top 15 for portfolio inclusion
- Generated random portfolio weight allocations and simulated portfolio performance
- Selected the portfolio weights that maximized the Sharpe ratio across simulations

## Technologies Used
- Python
- pandas, numpy
- yfinance
- datetime, math
- Jupyter Notebook

## Results
- Generated a ranked list of stocks based on composite technical scores aligned with the goal of beating the market


