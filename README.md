# 🛒 E-commerce Sales Analysis (SQL Project)

This project provides a complete SQL-based analysis of an e-commerce business. It simulates real-world sales operations and demonstrates how to use SQL to extract business insights from structured data.

---

## 📁 Project Structure

- `schema.sql` – SQL script to create the database schema (tables and relationships)
- `insert_data.sql` – Sample data inserts to simulate customer orders and payments
- `queries.sql` – Analytical queries for sales trends, customer behavior, and product performance

All components are included in the `E-commerce` file in this repository.

---

## 🧱 Database Schema

The project contains the following tables:

- **customers**: Customer info (name, email, city)
- **products**: Product catalog (name, category, price)
- **orders**: Order transactions by customers
- **order_items**: Items purchased in each order
- **payments**: Payment details for each order

### Entity Relationships:
- Each customer can have multiple orders
- Each order can include multiple products
- Each order has one associated payment

---

## 🔍 Sample Analytical Queries

- 📆 Total sales per month
- 🏆 Top 5 best-selling products
- 💰 Customer lifetime value
- 📦 Most popular product categories
- 🙋 Active customers with more than one order

---

## 🚀 Getting Started

1. Load the SQL script in your SQL engine (PostgreSQL, MySQL, SQLite, etc.)
2. Run the table creation and data insertion statements
3. Execute the analysis queries to generate insights

---

## 📊 Example Insight

> *"Electronics is the top-performing category by volume. Alice Smith is the highest value customer, and March shows strong monthly revenue growth."*

---

## 🛠️ Tech Stack

- SQL (PostgreSQL-compatible syntax)
- Any RDBMS (MySQL, SQLite, etc.)

---

## 📜 License

This project is open-source and free to use for educational or portfolio purposes.

---

## 🙌 Author

Created by Roobis

