# ATM Operations System (Java)

A console-based Java application that simulates real-time ATM functionalities. This project demonstrates the application of **Object-Oriented Programming (OOP)** principles and clean code practices.

## 🚀 Features
* **Account Authentication**: Simple PIN-based validation.
* **View Balance**: Check the current available balance in the account.
* **Withdraw Money**: Deduct a specific amount from the balance (with validation for insufficient funds).
* **Deposit Money**: Add funds to the account.
* **Mini Statement**: (Optional/Bonus) Track the history of transactions.

## 🛠️ Tech Stack
* **Language**: Java (JDK 8 or higher)
* **Concepts**: Interfaces, Encapsulation, Classes and Objects, Scanner Class.

## 📂 Project Logic
1.  **Validation**: The user enters an ATM Number and PIN.
2.  **Menu Selection**: A user-friendly menu is displayed using a `while(true)` loop and `switch-case`.
3.  **Operations**: 
    * Balance is stored in a private variable (Encapsulation).
    * Withdrawals check if `balance >= amount` before proceeding.

## 📖 How to Run
1. Clone the repository:
   `git clone https://github.com/your-username/atm-operations-java.git`
2. Compile the files:
   `javac ATM.java`
3. Run the application:
   `java ATM`
