🏦 Bank Account System (Java)
📌 Overview

This project is a menu-driven banking system implemented in Java using Object-Oriented Programming (OOP) concepts such as abstraction and inheritance.

The system allows users to perform basic banking operations like deposit, withdrawal, account transfer, and viewing account details.

🚀 Features
Deposit money into account
Withdraw money from account
Transfer account to another bank
Display account details
Menu-driven user interaction
🧠 Concepts Used
Abstract Classes
Inheritance
Method Overriding
Encapsulation
Scanner for user input
🏗️ Class Structure
1. account (Abstract Class)

Contains common properties and abstract methods.

Attributes:

Account Number
Name
Bank Name
IFSC Code
Phone Number
Balance

Methods:

deposit(double amt) (abstract)
withdraw(double amt) (abstract)
transferBank(String newBank, String newIFSC)
showDetails()
2. Bank (Derived Class)

Extends the account class and implements:

Deposit functionality
Withdraw functionality
3. Main Class
Contains the main method
Implements menu-driven logic using Scanner
Handles user interaction
📋 Menu Options
1. Deposit
2. Withdraw
3. Transfer Bank
4. Show Details
5. Exit
▶️ How to Run
Clone the repository:
git clone https://github.com/your-username/bank-account-system.git
Navigate to the folder:
cd bank-account-system
Compile the program:
javac Main.java
Run the program:
java Main
💻 Sample Output
1.Deposit
2.Withdraw
3.Transfer Bank
4.Show Details
5.Exit

Enter choice: 1
Enter amount: 1000
Deposited: 1000

Enter choice: 4

--- Account Details ---
Account No: 101
Name: RAM
Bank: SBI
IFSC: SBI0001
Phone: 9876543210
Balance: 6000
⚠️ Limitations
Only one account (b1) is actively used
No validation for negative inputs
No persistent storage (data resets after program ends)
🔧 Future Improvements
Add multiple account selection
Implement money transfer between accounts
Add file handling for data storage
Improve input validation
Create a graphical user interface (GUI)
📄 License

This project is for educational purposes
