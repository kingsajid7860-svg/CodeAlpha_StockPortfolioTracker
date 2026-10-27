📈 CodeAlpha Stock Portfolio Tracker

Task 2 — CodeAlpha Python Programming Internship

A simple, console-based Stock Portfolio Tracker developed using Python. It calculates the total value of your stock investments based on manually defined stock prices and the quantities you own.

✨ Features

Predefined Stock Prices: Stores stock prices in a Python dictionary.
Multiple Stock Entries: Add multiple stocks to your portfolio.
Portfolio Valuation: Calculates the value of each holding and the total investment value.
Formatted Summary: Displays stock symbols, quantities, prices, and holding values in a table.
File Handling: Optionally saves the portfolio summary to portfolio_summary.txt.
Simple User Interface: Uses console input and output for easy interaction.

🛠️ Technologies Used

Language: Python
Modules: No external packages required
Concepts: Dictionaries, variables, loops, conditional statements, user input, arithmetic operations, and file handling.

📊 Stock Prices

The program uses predefined stock prices stored in a dictionary in stock_tracker.py.
STOCK_PRICES = {
    "AAPL": 180,
    "TSLA": 250,
    "GOOGL": 140,
    "MSFT": 420,
    "AMZN": 185
}

Note: These are sample prices for demonstration purposes, not live market prices.

🚀 Getting Started

Requirements

Python 3.8 or newer
No additional libraries required

Installation and Execution
1. Clone the repository
git clone https://github.com/kingsajid7860-svg/CodeAlpha_StockPortfolioTracker.git

2. Navigate to the project directory
cd CodeAlpha_StockPortfolioTracker

3. Run the program
python stock_tracker.py

If needed, use python3 stock_tracker.py or py stock_tracker.py, depending on your system.
🎮 How to Use

Run the program.
Enter a stock symbol, such as AAPL.
Enter the quantity of shares you own.
Repeat for additional stocks.
Type done when you have finished entering stocks.
View the portfolio summary and total investment value.
Choose the option to save the summary if prompted.

💻 Example Output
Stock symbol: AAPL
Quantity of AAPL: 10

Stock symbol: TSLA
Quantity of TSLA: 5

Stock symbol: done

Stock     Qty    Price      Value
AAPL      10     $180       $1,800
TSLA      5      $250       $1,250

Total investment:             $3,050

Output formatting may vary depending on the program implementation.
📂 Project Structure
CodeAlpha_StockPortfolioTracker/
│
├── stock_tracker.py
├── README.md
└── portfolio_summary.txt   # Generated when the summary is saved

📚 Concepts Demonstrated

Python dictionaries for storing stock prices
Loops and conditional statements
Console input and output
Basic arithmetic calculations
String formatting for tabular output
File handling for saving portfolio summaries

👨‍💻 Author
Sajid Khan
Python Programming Intern — CodeAlpha

Developed as part of the CodeAlpha Python Programming Internship.
