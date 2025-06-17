# 🛒 Cash & Carry Management System

This is a command-line based retail store management system developed as a university project. It simulates the core functions of a Cash & Carry store using **Python** for the frontend interface and **PostgreSQL** for the database backend.

## 📌 Project Overview

The system is designed to help manage daily store operations such as:

- Employee and Address Management
- Customer Records
- Product Inventory
- Categories
- Supplier Management
- Purchase Orders
- Sales Processing

The goal was to build a working application that integrates database concepts with Python programming while keeping the interface simple and practical.

## 🧠 Features

- 🔍 Search customers by phone number
- 🧾 Record sales and purchases with item-level details
- ✅ Foreign key and constraint handling to ensure data integrity
- 🔁 Real-time updates to product quantity
- 📦 Manage categories and product inventory easily
- 🧑‍💼 Employee address management

## 🛠 Technologies Used

- **Python** (CLI interface)
- **PostgreSQL** (Relational database)
- **psycopg2** (Python-PostgreSQL adapter)

## 🚀 How to Run

1. Make sure you have PostgreSQL installed and running.
2. Create a new database and run the provided `.sql` file to create tables.
3. Edit the `connect_db()` function in the Python script with your DB credentials.
4. Run the Python script:
   ```bash
   python main.py
