# Stock Tracker

A simple Python program to track your stock portfolio. Add stocks, record how many shares you own, and see the current value and profit or loss of your investments.

## Features

- Add stocks with ticker symbol, quantity, and purchase price
- View your full portfolio in one table
- Fetch current stock prices
- Calculate total value and profit/loss per stock and overall
- Remove stocks from your portfolio
- Save and load portfolio data automatically

## Requirements

- Python 3.8 or higher
- yfinance (for live stock prices)

## Installation

1. Clone or download this repository:

   bash
   git clone https://github.com/your-username/stock-tracker.git
   cd stock-tracker
   

2. Install the dependencies:

   bash
   pip install -r requirements.txt
   

## Usage

Run the program:

bash
python stock_tracker.py


You will see a menu like this:


=== Stock Tracker ===
1. Add stock
2. View portfolio
3. Remove stock
4. Exit


Choose an option by typing its number and pressing Enter.

### Example


Enter choice: 1
Ticker symbol: AAPL
Number of shares: 10
Purchase price: 150.00
Stock added!

Enter choice: 2
Symbol  Shares  Bought   Current  Profit/Loss
AAPL    10      150.00   185.50   +355.00
-------------------------------------------
Total value: 1855.00   Total P/L: +355.00


## Project Structure


stock-tracker/
├── stock_tracker.py    # Main program
├── portfolio.json      # Saved portfolio data
├── requirements.txt    # Dependencies
└── README.md           # This file


## How It Works

- *Functions* handle each action (add, view, remove, save, load).
- *Loops* keep the menu running until you choose to exit.
- *Dictionaries/JSON* store your portfolio between sessions.
- *API calls* fetch the latest prices for each ticker.

## Future Improvements

- Price alerts when a stock hits a target
- Charts of price history
- Support for multiple portfolios
- Export to CSV or Excel
- Simple GUI or web interface

## Disclaimer

This project is for learning and personal use only. Prices may be delayed or inaccurate. It is not financial advice.

## License

This project is licensed under the MIT License.
