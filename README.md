# 🗄️ KxP Store SQL Database Project

## 📘 Project Objective

This project focuses on building and managing a sample retail database (**KxP_store**) using **SQL Server** to practice essential database design principles and querying skills. The core goal is to simulate a real-world store management system by applying **database normalization** and implementing table relationships.

---

## 📊 Key Features & Data Model

The database is composed of multiple related tables (products, customers, orders, shippers, statuses) to track the entire sales process.

### 🔑 Database Design Highlights:

* **Normalization:** Applied to minimize data redundancy.
* **Keys & Constraints:** Implemented **Primary Keys (PK)**, **Foreign Keys (FK)**, and **Composite Keys** to enforce data integrity and define relationships.
* **Data Tracking:**
    * **Products & Inventory:** Tracks product names, stock levels, and unit prices.
    * **Customers:** Stores customer details, addresses, and loyalty points.
    * **Orders & Order Items:** Captures customer orders with product details and quantities.
    * **Shippers & Order Status:** Monitors shipment details and delivery progress.

---

## 📈 SQL Queries Practiced

This project demonstrates proficiency in writing complex SQL queries for business intelligence:

* **Filtering & Conditions:** Identifying customers by age or address (`WHERE` + filters).
* **Data Aggregation:** Calculating total order value (`SUM` + `GROUP BY`).
* **Relationship Management:** Joining multiple tables (`JOIN`) to get detailed order and product insights.
* **Status Tracking:** Querying orders that haven't been shipped (`shipped_date IS NULL`).
* **Ranking:** Ranking top customers by loyalty points (`ORDER BY` + `OFFSET-FETCH`).

---

## ⚙️ Tools & Techniques Used

| Technique | Description |
| :--- | :--- |
| **SQL Server / SQL Syntax** | Primary environment for database creation and querying. |
| **DDL (Data Definition Language)** | Utilizing `CREATE TABLE` and applying data constraints. |
| **DML (Data Manipulation Language)** | Utilizing `INSERT INTO` and `UPDATE` for data management. |
| **Constraints** | Applying `PRIMARY KEY`, `FOREIGN KEY`, `IDENTITY`, and `DEFAULT`. |
| **Advanced Queries** | Applying `SELECT`, `JOIN`, `WHERE`, `GROUP BY`, `ORDER BY`, and Aggregate Functions. |

---

## 🧠 Key Learnings

* Improved practical understanding of **Relational Database Design** (PK, FK, Composite PK).
* Gained experience in writing **production-ready SQL queries** for common retail use cases.
* Enhanced ability to apply filtering, sorting, aggregations, and joins effectively to solve real-world problems.

---

## 🔗 Project Overview

This database serves as a robust foundation for future reporting, allowing analysis of:

* Identifying top customers and their purchase history.
* Analyzing product performance and stock availability.
* Tracking unshipped or pending orders.
