# Momentum Trading Strategy

A Python implementation of a momentum-based trading strategy for stocks. The strategy analyzes price momentum using historical data to generate trading signals and evaluate performance against a buy-and-hold approach.

## Overview

The strategy:
- Calculates momentum using 10-day returns
- Takes long positions when momentum is in the top 10th percentile
- Compares performance against buy-and-hold strategy
- Provides visualization of strategy performance

## Key Features

- Data retrieval using yfinance
- Momentum calculation and signal generation
- Performance metrics calculation:
  - Total Return
  - Sharpe Ratio
  - Maximum Drawdown
- Strategy visualization using matplotlib

## Implementation

The implementation is contained in a Jupyter notebook that:
1. Fetches historical stock data
2. Calculates momentum indicators
3. Generates trading signals
4. Evaluates strategy performance
5. Visualizes results through comparison charts

## Usage

Open the `momentum_strategy.ipynb` notebook in Jupyter and run all cells. The notebook is well-documented with comments explaining each step of the implementation.
