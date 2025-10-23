# -CODSOFT-ATM-INTERFACE

# 💳 ATM Interface (Java GUI)

A simple **ATM Machine Simulation** built using **Java Swing** and **Object-Oriented Programming (OOP)** principles.  
This project demonstrates basic banking operations like **deposit**, **withdraw**, and **balance inquiry** using a graphical interface.

---

## 🚀 Features
- 🏦 **Deposit Money** into the account
- 💸 **Withdraw Money** (with balance validation)
- 📊 **Check Account Balance**
- 🧮 **Input validation** for valid and sufficient balance
- 💬 **Real-time messages** for user feedback
- 🎨 **User-friendly Swing GUI**

---

## 🧩 Technologies Used
- **Java (JDK 8 or higher)**
- **Swing GUI Library**
- **Object-Oriented Programming (OOP)** concepts

---

## 🧠 OOP Concepts Used
- **Encapsulation** → BankAccount class hides balance details  
- **Abstraction** → ATMInterface handles user interaction  
- **Composition** → ATMInterface “has a” BankAccount  

---

## 🏗️ Project Structure
ATMInterface.java
│
├── class BankAccount
│ ├── getBalance()
│ ├── deposit(amount)                                                 
│ └── withdraw(amount)
│
└── class ATMInterface (GUI)

├── depositButton
├── withdrawButton
├── checkButton
└── clearButton

 <img width="491" height="511" alt="Screenshot 2025-10-23 125815" src="https://github.com/user-attachments/assets/f0fec391-849a-4a7f-b1d9-4439ae28457c" />

 ## 🧮 Example Usage

### 🏁 Starting Balance
`₹1000.00`

### 💰 Deposit Example
Input: 500  
→ Output: ✅ Deposited ₹500  
New Balance: ₹1500  

### 💸 Withdraw Example
Input: 200  
→ Output: ✅ Withdrawn ₹200  
New Balance: ₹1300  

### ⚠️ Invalid Withdraw Example
Input: 2000  
→ Output: ⚠️ Insufficient Balance!  


<img width="479" height="502" alt="Screenshot 2025-10-23 130454" src="https://github.com/user-attachments/assets/3e76b75d-3ce2-4c2f-900b-9d6b45e91203" />

---

