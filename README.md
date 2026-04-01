# 🏦 Bank Management System

A desktop-based banking application built using **Java, Swing, and JDBC** that allows users to perform core banking operations such as account creation, deposits, withdrawals, and transaction management.

---

## 🚀 Features

* 🔐 User authentication (Login system)
* 📝 Multi-step account registration
* 💰 Deposit money
* 💸 Withdraw money
* ⚡ Fast cash (quick withdrawal options)
* 📊 Balance inquiry
* 📄 Mini statement (transaction history)
* 🔑 PIN change functionality

---

## 🧠 Tech Stack

**Frontend:**

* Java Swing
* AWT

**Backend:**

* Core Java
* JDBC

**Database:**

* MySQL

---

## 📂 Project Structure

```
Bank-Management-System/
├── src/bank/management/system/
│   ├── Login.java
│   ├── Signup.java
│   ├── Signup2.java
│   ├── Signup3.java
│   ├── Deposit.java
│   ├── Withdrawl.java
│   ├── BalanceEnquiry.java
│   ├── FastCash.java
│   ├── Pin.java
│   ├── mini.java
│   ├── Connn.java
│   └── main_Class.java
│
├── src/icon/   # Images and UI assets
└── README.md
```

---

## ⚙️ Installation & Setup

### 🔹 1. Clone the repository

```bash
git clone https://github.com/your-username/bank-management-system.git
cd bank-management-system
```

---

### 🔹 2. Setup Database (MySQL)

```sql
CREATE DATABASE bankmanagementsystem;
```

```sql
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
```

---

### 🔹 3. Configure Database Connection

Update credentials in:

```
Connn.java
```

---

### 🔹 4. Run the Project

* Open in **IntelliJ IDEA / Eclipse**
* Run:

```java
main_Class.java
```

---

## 🔐 Authentication Flow

* User signs up through multi-step registration
* System generates card number and PIN
* User logs in using credentials
* Access granted to banking dashboard

---

## 🔄 Application Flow

```
User → Login/Signup → Dashboard → Banking Operations → Database → Response → UI Update
```

---

## 📌 Key Learnings

* Object-Oriented Programming (OOP)
* Java Swing GUI development
* JDBC database connectivity
* Event-driven programming
* Real-world banking system design

---

## 🚀 Future Improvements

* Add OTP-based authentication
* Convert to web-based application (Spring Boot + React)
* Add transaction filters and reports
* Improve UI using JavaFX

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📧 Contact

If you have any questions or suggestions, feel free to reach out.

---

⭐ **If you like this project, don’t forget to star the repository!**
