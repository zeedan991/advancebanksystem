
# 🏦 Java Bank Account Management CLI

A simple **Command-Line Bank Account System** implemented in Java.  
This program allows a user to create an account, credit and withdraw funds, view balance, and display their PIN.

---

## 📌 Features

- Create a new bank account with:
- Account holder name
- PIN (validated against negative values)
- Initial balance
- Automatic account number generation
- Deposit (Credit) money
- Withdraw money with **insufficient balance check**
- View account balance
- Display account PIN
- **Input validation** (handles invalid numbers, negative amounts, etc.)
- **Does not crash on wrong input** — loops until valid choice is given
- Exit to main menu or quit the program at any time

---
## 📂 Project Structure

Classes:
- **createAccout** → Stores account details and generates account number.
- **mainprocess** → Handles account operations (credit, withdraw, balance check, show PIN).
- **assignment4** → Main program with menu loops and exception handling.

---

## 🚀 How to Run

1. **Clone this repository**:
  git clone https://github.com/zeedan991/java-bank-cli.git
  cd java-bank-cli

3. **Compile the Program**:
  javac assignment4.java

4. **Run the Program**:
  java assignment4
---

## 💻 Usage Example
=== BANK ACCOUNT SYSTEM ===

Create new account and perform transactions.

Exit.

Enter your choice: 1.

Enter account holder name : John Doe.

Enter pin: 1234.

Enter initial balance: 5000.

ACCOUNT NUMBER FOR John Doe is : 2001.

BALANCE IN ACCOUNT NUMBER 2001 is 5000.00.

--- Account Menu ---

Credit

Withdraw

View Balance

Display PIN

Exit to Main Menu
Choose option: 1
Enter amount to credit: 1500
AMOUNT CREDITED, NEW BALANCE: 6500.0


---

## ⚠ Error Handling
- If you enter a non-number (e.g., text instead of a number), the program will **prompt again** without stopping.
- Negative amounts are not allowed.
- PIN cannot be negative or zero.
- Withdrawals that exceed balance will throw `INSUFFICIENT BALANCE` error.

---



## ✨ Author
- **zeedan khatik**  
  📧 zeedankhatik@gmail.com  
  🌐 [GitHub Profile](https://github.com/zeedan991)
