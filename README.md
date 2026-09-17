# ATM Interface in Java 💳

A simple console-based ATM Interface developed using Java and Object-Oriented Programming concepts.

## 📌 Project Overview

This project simulates basic ATM operations through a command-line interface.

The user can:

* Check account balance
* Deposit money
* Withdraw money
* Exit the ATM

The project demonstrates basic Java concepts such as classes, objects, constructors, methods, encapsulation, conditional statements, switch-case, loops, and user input.

## 🚀 Features

* 💰 Check Balance
* ➕ Deposit Money
* ➖ Withdraw Money
* ⚠️ Insufficient Balance Validation
* ⚠️ Invalid Amount Validation
* 🔄 Menu repeats until the user chooses Exit

## 🛠️ Technologies Used

* Java
* Java Scanner
* Object-Oriented Programming (OOP)

## 📚 OOP Concepts Used

### 1. Class

The project contains two classes:

```text
BankAccount
ATM
```

### 2. Object

A `BankAccount` object is created using:

```java
BankAccount account = new BankAccount(5000);
```

### 3. Constructor

The constructor initializes the account with an initial balance:

```java
BankAccount(double initialBalance)
```

### 4. Encapsulation

The account balance is declared as private:

```java
private double balance;
```

This prevents direct access to the balance from outside the `BankAccount` class.

### 5. Methods

The `BankAccount` class contains:

```text
deposit()
withdraw()
checkBalance()
```

## 📂 Project Structure

```text
ATM-Interface-Java/
│
├── ATM.java
└── README.md
```

## ▶️ How to Run

### Step 1: Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/ATM-Interface-Java.git
```

### Step 2: Open the project

Open the project folder in VS Code, IntelliJ IDEA, Eclipse, or any Java-supported IDE.

### Step 3: Compile the program

```bash
javac ATM.java
```

### Step 4: Run the program

```bash
java ATM
```

## 💻 Sample Menu

```text
===== ATM MENU =====
1. Check Balance
2. Deposit Money
3. Withdraw Money
4. Exit
Enter your choice:
```

## 🔐 Initial Balance

The account starts with:

```text
₹5000
```

This can be changed in:

```java
BankAccount account = new BankAccount(5000);
```

## 🎯 Learning Objective

The main objective of this project is to understand how Java OOP concepts can be used to build a simple real-world application.

## 👩‍💻 Author

Princess Pundir

GitHub: https://github.com/princesspundir

LinkedIn: https://www.linkedin.com/in/princess-pundir-72487a382/
