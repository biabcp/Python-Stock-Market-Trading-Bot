# Python-Stock-Market-Trading-Bot
Buy and Sell per 20 Day Moving Average Signals
# Stock Trading Simulation

This project is a simple stock trading simulation that reads historical stock price data, calculates moving averages, and generates simulated buy and sell trading actions based on moving average crossovers.

## Features

- Reads historical stock price data from a CSV file.
- Calculates 20-day and 50-day moving averages.
- Simulates buying and selling stocks based on moving average crossovers.

## Prerequisites

- Python 3.x is installed.
- Required Python packages (`pandas` and `numpy`) are installed.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/stock-trading-simulation.git

Install the required packages:
pip install pandas numpy

Usage
Prepare your stock price data CSV file (aapl_stock_prices.csv in this case) with columns like "Date" and "Close".

Launch a terminal and navigate to the project directory.

Run the simulation script:
python stock_trading_simulation.py
The script will read the stock price data, calculate moving averages, and simulate trading actions based on moving average crossovers.

Notes
This simulation is a basic example and doesn't consider real-world trading complexities.
The trading strategy used (moving average crossovers) is simplified for educational purposes.
Always perform thorough research and analysis before making real trading decisions.
Adjust the script for different trading strategies or additional indicators.
Ensure you have the necessary permissions to access and use stock price data.

Acknowledgements
This project is inspired by the interest in stock trading simulations and is provided as-is for educational purposes.
