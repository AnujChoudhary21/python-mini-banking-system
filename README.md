# python-mini-banking-system
A Python-based Mini Banking System featuring account creation, deposits, withdrawals, transaction tracking, balance management, and exception handling.

## 📌 Project Overview

The **Mini Banking System** is a beginner-level Python project that simulates basic banking operations. It allows users to create accounts, deposit and withdraw money, track transactions, and view account summaries.

The project focuses on applying core Python programming concepts to a practical, real-world-inspired problem.

## ✨ Features

- **Account Creation:** Create accounts with an initial balance.
- **Deposit Money:** Add money to an existing account.
- **Withdraw Money:** Withdraw money while checking the account balance.
- **Transaction History:** Record deposits and withdrawals.
- **Account Summary:** Display the current balance and transaction history.
- **Input Validation:** Reject negative initial balances and non-positive transaction amounts.
- **Exception Handling:** Handle errors such as insufficient funds, duplicate accounts, and missing accounts.
- **Account Lookup:** Find accounts using case-insensitive name matching.

## 🛠️ Technologies Used

- Python 3
- Lists and Dictionaries
- Functions and Modular Programming
- Conditional Statements and Loops
- Exception Handling (`try-except`, `raise`)
- String Methods and Formatted Strings (f-strings)

## 📂 Project Structure

```text
python-mini-banking-system/
│
├── mini_banking_system.py
├── README.md
└── .gitignore
```

## ▶️ How to Run

1. Install Python 3.
2. Clone this repository or download the Python file.
3. Open a terminal in the project directory.
4. Run the following command:
                             mini_banking_system.py

The program executes predefined test scenarios demonstrating account creation, deposits, withdrawals, error handling, and account summary display.

## 🧪 Test Scenarios

- Create an account with an initial balance.
- Deposit money multiple times.
- Withdraw money from the account.
- Attempt a withdrawal exceeding the available balance.
- Attempt to create a duplicate account.
- Display the final account balance and transaction history.

## 📚 Key Learnings

- Organizing code into reusable functions.
- Managing structured data using lists and dictionaries.
- Updating account balances through transactions.
- Validating operations and raising exceptions.
- Using function calls to connect different parts of a program.
- Testing normal operations and handling error scenarios.

## ⚠️ Limitations

- Account data is stored in memory and is lost when the program ends.
- Accounts are identified by account holder names rather than unique account IDs.
- The project is an educational simulation and is not intended for real banking transactions.
- Interactive user input and persistent database storage are not implemented.

## 🚀 Future Enhancements

- Add an interactive menu-driven interface.
- Assign unique account IDs.
- Store account information using SQLite or another database.
- Add transaction timestamps and transaction IDs.
- Improve financial amount validation and precision.
- Add automated unit tests using Python's `unittest` or `pytest`.

