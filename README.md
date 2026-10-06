# 💰 Expense Tracker

A simple command-line expense tracker written in Python, with JSON data persistence.

## 🎯 About the project

Expense Tracker is a terminal-based application that allows users to manage their expenses.

The project was created to practice Python fundamentals while building a complete small application with persistent data.

Expenses are stored in a JSON file, allowing the data to remain available when the program is closed and reopened.

## 🛠️ Technologies

- **Python 3**
- `json`
- `datetime`
- `pathlib`
- `os`

## ⚙️ Features

- ➕ Add an expense
- 📋 Display saved expenses
- 🗑️ Delete an expense
- 💰 Calculate the total amount spent
- 💾 Save expenses in a JSON file
- 📅 Store the date and time of each expense
- 🏷️ Categorize expenses
- 🔤 Give each expense a name
- ✅ Validate user input
- 💶 Accept decimal amounts using `,` or `.`

Each expense contains:

```text
Amount
Category
Name
Date
```

## 💾 Data persistence

The application uses a JSON file to store expenses.

The file is located relative to the Python program using `pathlib`, allowing the application to keep its data between executions.

Example:

```text
ExpenseTracker/
├── ExpenseTracker.exe
└── expenses.json
```

## 📚 What I learned

This project helped me practice several important Python concepts:

- Lists and dictionaries
- `while` and `for` loops
- `match/case`
- `try/except`
- Input validation
- `break` and `continue`
- `pop()`
- Type conversion
- Working with dates using `datetime`
- Reading and writing JSON files
- Working with file paths using `pathlib`
- Building a menu-driven command-line application

## 🚀 Possible improvements

Future versions could include:

- [ ] Search expenses by category
- [ ] Filter expenses by date
- [ ] Monthly spending statistics
- [ ] Export data to CSV
- [ ] Graphs and spending summaries
- [ ] Budget limits
- [ ] Graphical user interface
- [ ] Database support instead of JSON

## 📦 Download

The project can be distributed as a standalone Windows executable.

See the **Releases** section to download the application.

## 👨‍💻 Author

**Sir Edoww**

Student in Computer Science Engineering — IG2I, Centrale Lille.

This project was created as part of my personal programming practice.
