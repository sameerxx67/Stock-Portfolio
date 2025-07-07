# Stock-Portfolio
A simple Python-based Stock Portfolio Tracker that calculates total investment, current value, and profit/loss from manually defined stocks — built as part of the CodeAlpha Internship.

# 📈 CodeAlpha_StockPortfolioTracker

This is a console-based **Stock Portfolio Tracker** built using Python as part of the **CodeAlpha Internship** program.

It allows users to define a list of stocks (symbol, shares, buy price, current price) and calculates:
- Total investment made
- Current value of portfolio
- Overall profit or loss

The tracker is designed for beginners to practice working with lists, dictionaries, loops, and basic financial calculations in Python.

---

## ✅ Features

- Tracks multiple stocks manually
- Calculates:
  - Investment per stock
  - Current value per stock
  - Profit or loss per stock
  - Total investment and total current value
  - Overall profit/loss
- Clean and readable console output

---

## 🛠️ Technologies Used

- Python 3
- No external libraries — only core Python

---

## 🧠 Concepts Practiced

- Lists and Dictionaries
- `for` loops and arithmetic operations
- Clean code formatting
- Console output formatting
- Real-world problem solving with Python

---

## 📦 How It Works

The data is stored as a list of dictionaries like this:

```python
portfolio = [
    {"symbol": "AAPL", "shares": 10, "buy_price": 150, "current_price": 175},
    {"symbol": "GOOGL", "shares": 5, "buy_price": 2000, "current_price": 2100},
    ...
]

