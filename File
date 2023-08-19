import pandas as pd
import numpy as np

def buy_stock(symbol, price):
    """Buys a stock."""
    print("Buying {} at {}".format(symbol, price))

def sell_stock(symbol, price):
    """Sells a stock."""
    print("Selling {} at {}".format(symbol, price))

def main():
    # Get the stock price data.
    data = pd.read_csv("aapl_stock_prices.csv")

    # Calculate the 20 day moving averages.
    data["short_ma"] = data["Close"].rolling(window=20).mean()
    data["long_ma"] = data["Close"].rolling(window=50).mean()

    # Loop over the data and trade the stock.
    for index, row in data.iterrows():
        if row["Close"] > row["short_ma"] and row["Close"] > row["long_ma"]:
            buy_stock("AAPL", row["Close"])
        elif row["Close"] < row["short_ma"] and row["Close"] < row["long_ma"]:
            sell_stock("AAPL", row["Close"])

if __name__ == "__main__":
    main()
