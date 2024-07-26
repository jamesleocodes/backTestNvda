# NVDA Moving Average Crossover Backtesting

## Overview

This repository contains code to backtest a moving average crossover trading strategy using historical data for NVIDIA Corporation (NVDA) from July 25, 2023, to July 25, 2024. The goal is to evaluate the effectiveness of this strategy based on past market performance.

## Strategy

The strategy utilizes two moving averages:
- **50-Day Moving Average (Short MA)**: Reacts quickly to price changes.
- **200-Day Moving Average (Long MA)**: Smooths out price fluctuations over a longer period.

### Signals
- **Buy Signal**: Triggered when the 50-day MA crosses above the 200-day MA.
- **Sell Signal**: Triggered when the 50-day MA crosses below the 200-day MA.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
2. Install the required packages
   ```bash
   pip install pandas numpy matplotlib
## Usage 
1. Place your historical data in a CSV file named NVDA.csv. Ensure it contains 'Date' and 'Close' columns.
2. Run backtesting notebook.
3. The results will be visualized in a plot showing:
   - Closing prices
   - Moving averages
   - Buy and sell signals
     
### Conclusion
This backtesting analysis provides valuable insights into the performance of the moving average crossover strategy for NVDA during the specified period. It serves as a foundation for further exploration and refinement of trading strategies based on historical data.
