🏦 Bank Management System

A desktop-based Bank Management System built using Java (Swing) and JDBC, designed to simulate core banking operations such as account creation, deposits, withdrawals, balance inquiry, and transaction history.

🚀 Features
🔐 User Authentication (Login System)
📝 Multi-step Account Registration (Signup Forms)
💰 Deposit Money
💸 Withdraw Money
⚡ Fast Cash (Quick Withdraw Options)
📊 Balance Inquiry
📄 Mini Statement (Transaction History)
🔑 PIN Change Functionality
🛠️ Tech Stack
Language: Java
UI Framework: Swing (Java GUI)
Database: MySQL
Connectivity: JDBC
📂 Project Structure
Bank Management System/
│
├── src/bank/management/system/
│   ├── Login.java
│   ├── Signup.java / Signup2.java / Signup3.java
│   ├── Deposit.java
│   ├── Withdrawl.java
│   ├── BalanceEnquiry.java
│   ├── FastCash.java
│   ├── Pin.java
│   ├── mini.java
│   ├── Connn.java (Database Connection)
│   └── main_Class.java
│
├── src/icon/ (Images & UI assets)
└── README.md
⚙️ Setup Instructions
1. Clone the Repository
git clone <your-repo-link>
cd Bank-Management-System
2. Configure Database (MySQL)

Create a database:

CREATE DATABASE bankmanagementsystem;

Create required tables (example):

CREATE TABLE login (
    formno VARCHAR(20),
    cardnumber VARCHAR(25),
    pin VARCHAR(10)
);

CREATE TABLE bank (
    pin VARCHAR(10),
    date VARCHAR(50),
    type VARCHAR(20),
    amount VARCHAR(20)
);

👉 Update DB credentials in:

Connn.java
3. Run the Project
Open in IntelliJ IDEA / Eclipse
Run:
main_Class.java
🔄 Application Flow
User signs up → gets account details
Logs in using card number & PIN
Access ATM interface:
Deposit / Withdraw
Fast Cash
Balance Check
Mini Statement
All transactions stored in database
🧠 Key Concepts Used
OOP (Encapsulation, Classes, Objects)
Event Handling (Swing)
JDBC (Database Connectivity)
Multi-screen Navigation
Basic Banking Logic Implementation
🎯 Use Case

This project is ideal for:

Learning Java GUI development
Understanding JDBC + Database integration
Demonstrating real-world system design in interviews
💡 Future Enhancements
Add OTP-based authentication
Implement online banking (web version)
Add transaction filtering & reports
Improve UI using JavaFX or React frontend
👨‍💻 Author

Pushpraj Verma

⭐ If you like this project

Give it a ⭐ on GitHub and share it!
