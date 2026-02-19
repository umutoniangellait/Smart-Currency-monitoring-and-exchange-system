Currency Exchange System
 Project Overview

The Currency Exchange System is a full-stack application designed to allow users to convert currencies based on current exchange rates. The system enables customers to perform currency exchange transactions while administrators manage and update exchange rates.

This project demonstrates practical implementation of:

Database Design

Backend Logic

User Authentication

Transaction Processing

Role-Based Access Control

System Documentation

 Project Objectives

Allow users to convert currencies in real-time

Store and manage exchange rates

Record transaction history

Implement secure authentication

Enforce relational database integrity

Apply normalization and constraints

👥 User Roles
👤 Customer

Register and login

View available currencies

Perform currency exchange

View transaction history

👨‍💼 Admin

Login securely

Add new currencies

Update exchange rates

Monitor transactions

🗂️ System Architecture

The system consists of:

1️⃣ Frontend

Handles user interaction and displays:

Login & Registration

Currency selection

Exchange calculator

Transaction history

2️⃣ Backend

Handles:

Business logic

Authentication

Currency calculations

Database communication

3️⃣ Database

Relational database designed using ER modeling and normalization.

Main Tables:

User

Admin

Currency

Transaction

🔗 Database Relationships

One User → Many Transactions (1:N)

One Currency → Many Transactions (1:N)

One Admin → Many Currencies (1:N)

Foreign key constraints ensure referential integrity.

🛡️ Security Features

Encrypted passwords

Role-based access control

Input validation

Database constraints

Secure transaction recording

🧱 Technologies Used

Programming Language: (Add yours e.g., Java / Python / PHP / C#)

Database: MySQL

SQL

ER Diagram Tool: Draw.io

Version Control: Git & GitHub

📂 Project Structure
Currency-Exchange-System/
│
├── database/
│   ├── schema.sql
│   └── data_dictionary.md
│
├── backend/
│   └── (application files)
│
├── frontend/
│   └── (UI files)
│
├── docs/
│   ├── ERD.png
│   └── project_report.pdf
│
└── README.md

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/currency-exchange-system.git


Set up the database:

Open MySQL

Run the provided SQL script

Configure database connection in backend files.

Run the application.

📊 Features Implemented

✔ User registration and login
✔ Admin management panel
✔ Currency rate management
✔ Exchange rate calculation
✔ Transaction storage
✔ Data validation
✔ Normalized relational database



Referential Integrity

Backend Integration

System Documentation

Version Control using GitHub
