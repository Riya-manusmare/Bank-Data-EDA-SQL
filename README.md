# 🏦 MyBankDB – Banking Database Project

## 📌 Overview

This project demonstrates the design and querying of a sample banking database called **`mybankdb`**. It includes tables for **Customers, Accounts, Transactions, Loans, CreditCards, Branches, and ATMs**. The project showcases SQL operations such as data retrieval, aggregation, filtering, joins, and data manipulation queries used in a real-world banking scenario.

## 🗂️ Database Structure

The database contains the following tables:

* **Customers** – Stores customer information such as name, age, and customer ID.
* **Accounts** – Stores account details like account type, balance, and status.
* **Transactions** – Records all transactions (date, amount, type).
* **Loans** – Keeps track of loan amounts, interest rates, and end dates.
* **CreditCards** – Holds information on credit limits and balances.
* **Branches** – Information about bank branches.
* **ATMs** – Stores ATM locations and status.

## 📝 Features of the Project

### 🔹 Basic Queries

* Retrieve all data from key tables (Customers, Accounts, Transactions, Loans, etc.).
* Filter results (active accounts, loans above certain rates, transactions after a specific date).

### 🔹 Aggregate Queries

* Total number of customers and accounts.
* Total loan amounts and credit card limits.
* Average age of customers.
* Sum of transactions for each account per month.

### 🔹 Join Operations

* Combine customer details with their account information.
* Combine transaction details with account and customer data.
* Find customers with multiple accounts.

### 🔹 Subqueries

* Find the 5th highest loan amount without using `LIMIT`.
* Retrieve the second highest loan amount.

### 🔹 Data Manipulation

* Delete inactive accounts.
* Clone the Customers table to a new table.

### 🔹 Special Queries

* Show only odd rows from the customers table.
* Split customer names into first and last name.
* Categorize customers into age groups (below 30, 30–60, above 60).
* Calculate days remaining for loan repayment.
* Find the latest transaction date for each account.

## ⚙️ How to Use

1. Run the provided SQL script in your MySQL or compatible database system.
2. Create the database and tables as per the script.
3. Use the example queries to explore and analyze the data.

## 🎯 Learning Outcomes

* Understanding how to design a banking database.
* Writing SQL queries for data retrieval, aggregation, and analysis.
* Using joins and subqueries effectively.
* Implementing data manipulation and conditional logic in SQL.

## 🧑‍💻 Technologies Used

* **MySQL / MariaDB**
* **SQL (Structured Query Language)**

## 📬 Contact

If you have any questions or suggestions, feel free to reach out or open an issue in this repository.

