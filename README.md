# Bank Account Simulation 🏦

A simple Python implementation of a bank account system, demonstrated in a Jupyter Notebook. This project showcases essential banking operations and serves as a great introduction to object-oriented programming in Python.

## Features
- **Account Creation**: Create an account with an owner and an optional initial balance (default is 0).
- **Deposit Funds**: Add money to the account with confirmation messages.
- **Withdraw Funds**: Withdraw money with balance checks and appropriate notifications for insufficient funds.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/deepakmalikk/bank-account-simulation.git
   cd bank-account-simulation

2. Open the notebook:
   ```
   jupyter notebook Bank-Account-Simulation.ipynb

3. Explore the code and run the cells to see the account simulation in action.

## Example
```
# Create an account
account = Account(owner="John Doe", balance=100)

# Deposit money
print(account.deposit(50))  # Output: "Deposit Accepted"

# Withdraw money
print(account.withdraw(30))  # Output: "Withdrawal Accepted"
print(account.withdraw(200))  # Output: "Funds Unavailable!"



