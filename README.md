# Banking-System-using-Java-with-Abstraction-and-Menu-Driven-Approach
menu-driven banking application developed in Java using object-oriented programming concepts like abstraction, inheritance, and method overriding

Banking System using Java
Overview

This project is a menu-driven banking system developed in Java using Object-Oriented Programming (OOP) concepts. It simulates basic banking operations such as deposit, withdrawal, money transfer, and transferring an account from one bank to another.

Features
Deposit money
Withdraw money
Transfer money between accounts
Transfer account from one bank to another (e.g., SBI to HDFC)
Display account details
Menu-driven interface using switch-case
Concepts Used
Abstraction (abstract class and methods)
Inheritance
Method Overriding
Encapsulation (basic)
Switch Case
Looping (do-while)
User input using Scanner
Project Structure
Main.java
 ├── abstract class account
 ├── class Bank extends account
 └── class Main (contains main method)
How It Works
The program displays a menu with options.
The user selects an operation (1–6).
Based on the input:
Deposit adds money to the account
Withdraw deducts money from the account
Transfer Money sends money to another account
Transfer Bank updates the bank name and IFSC
Show Details displays account information
The program continues until the user selects Exit.
Sample Run
1.Deposit 2.Withdraw 3.Transfer Money 4.Transfer Bank 5.Show Details 6.Exit
Enter your choice: 1
Enter amount: 500
Deposited: 500

Enter your choice: 5
--- Account Details ---
Account No: 101
Name: RAM
Bank: SBI
Balance: 5500
Requirements
Java JDK 8 or above
Any IDE (Eclipse, IntelliJ, VS Code) or Command Prompt
How to Run
Save the file as Main.java
Compile the program:
javac Main.java
Run the program:
java Main
Key Highlights
Simple and easy to understand
Demonstrates real-world banking operations
Clear implementation of OOP concepts
Suitable for academic use
Conclusion

This project demonstrates the use of Java OOP concepts to build a simple banking system. It helps in understanding abstraction, inheritance, and menu-driven programming.

Author

Sharmila Dinesh
