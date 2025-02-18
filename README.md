# Stock Momentum Trading Strategy

A simple implementation of a momentum-based trading strategy using Python and common financial libraries.

## Overview
This project demonstrates:
- Financial data handling with pandas
- Momentum strategy implementation
- Performance analysis and visualization
- Real-world trading strategy evaluation

## Requirements
```bash
pip install -r requirements.txt
```

## Usage
Open `momentum_strategy.ipynb` in Jupyter Notebook or Jupyter Lab:
```bash
jupyter notebook momentum_strategy.ipynb
```

## Strategy Details
- Uses 10-day returns to measure momentum
- Takes long positions when momentum is strong
- Compares against buy-and-hold benchmark
- Includes key performance metrics (Sharpe ratio, max drawdown)
