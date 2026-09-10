# 🚗 Motor Insurance SQL Project

## 📌 Project Overview

This project is a **Motor Insurance Database Management System** developed using **SQL**.

The database is designed to support a motor insurance platform where customers can receive insurance quotes, calculate premiums, make payments, and have policies issued. The system supports both **B2B broker-driven sales** and **B2C direct sales**.

The project demonstrates practical SQL concepts including database design, relationships, CRUD operations, joins, aggregation, subqueries, window functions, transactions, views, stored procedures, triggers, and query optimization.

---

## 🎯 Business Objectives

The database is designed to manage:

- 👤 Customers and their information
- 🚘 Customer vehicles
- 🏢 Insurance brokers
- 👨‍💼 Application users and roles
- 📍 Regional business information
- 🛡️ Insurance products
- 💰 Premium rates and pricing rules
- 📄 Insurance quotes
- 💳 Payments and currency conversion
- 📋 Issued insurance policies
- 📊 Regional and broker-level reporting

The system supports the complete workflow:

**User → Quote → Payment → Policy**

---

## 🗄️ Database Schema

The project contains the following main tables:

| Table | Purpose |
|---|---|
| `regions` | Stores regional and location information |
| `app_users` | Stores users and their roles |
| `brokers` | Stores broker organizations and financial details |
| `customers` | Stores customer information |
| `vehicles` | Stores vehicles linked to customers |
| `products` | Stores insurance product definitions |
| `premium_rates` | Stores insurance pricing rules |
| `quotes` | Stores generated insurance quotes |
| `payments` | Stores payment and settlement information |
| `policies` | Stores issued insurance policies |

---

## 🛠️ SQL Concepts Covered

- SELECT, WHERE, ORDER BY, DISTINCT
- GROUP BY and HAVING
- Aggregate functions
- INNER JOIN, LEFT JOIN, RIGHT JOIN
- FULL OUTER JOIN using UNION ALL
- CASE, BETWEEN, IN, LIKE
- Subqueries
- ALL and ANY operators
- LAG and LEAD
- ROW_NUMBER, RANK, DENSE_RANK
- NTILE
- Transactions and Savepoints
- ROLLBACK and COMMIT
- Views
- Stored Procedures
- Triggers
- Indexing
- EXPLAIN for query optimization

---

## 📊 Business Analysis

The project includes SQL queries for:

- Customer analysis
- Vehicle category analysis
- Broker performance
- Quote analysis
- Regional policy reporting
- Premium collection
- Currency-wise payment analysis
- Broker commission calculation
- High-value customer identification
- Premium ranking and quartile analysis

---

## ⚙️ Advanced SQL

### Stored Procedure

A stored procedure increases a premium by **5%** using an `INOUT` parameter.

### Trigger

A trigger prevents duplicate vehicle registration numbers from being inserted into the database.

### Transactions

The project demonstrates:

```sql
START TRANSACTION;
SAVEPOINT;
ROLLBACK TO SAVEPOINT;
COMMIT;
```

### Views

A regional policy collection view is created to simplify regional reporting.

### Indexing

The project demonstrates query optimization using indexes and `EXPLAIN`.

---

## 💻 Technologies Used

- **MySQL**
- **SQL**
- MySQL Workbench
- Relational Database Management
- Window Functions
- Stored Procedures
- Triggers
- Transactions
- Views
- Indexing

---

## 🚀 How to Run

1. Install **MySQL Server** and MySQL Workbench.
2. Create a new database.
3. Execute the table creation queries.
4. Insert the sample data.
5. Execute the SQL analysis queries.
6. Run the advanced SQL scripts for views, procedures, triggers, transactions, and indexes.

---

## 📁 Suggested Repository Structure

```text
motor-insurance-sql-project/
│
├── README.md
├── database/
│   ├── 01_create_tables.sql
│   ├── 02_insert_data.sql
│   ├── 03_basic_queries.sql
│   ├── 04_joins.sql
│   ├── 05_subqueries.sql
│   ├── 06_window_functions.sql
│   ├── 07_transactions.sql
│   ├── 08_views.sql
│   ├── 09_stored_procedures.sql
│   ├── 10_triggers.sql
│   └── 11_indexes.sql
│
└── screenshots/
    └── query-results/
```

---

## 👨‍💻 Author

**Madhankumar S**

📧 **Email:** madhansekar0908@gmail.com

---

## ⭐ Conclusion

The Motor Insurance SQL Project demonstrates how a real-world insurance business process can be designed and managed using a relational database.

It combines fundamental and advanced SQL techniques to manage **customers, vehicles, brokers, insurance products, quotes, payments, and policies**, while also providing analytical reporting and database optimization capabilities.