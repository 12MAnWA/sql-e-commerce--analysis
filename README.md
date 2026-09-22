# SQL E-Commerce Analysis

## Project Overview

This project is an e-commerce data analysis project built using SQL.

The purpose of the project is to practice and demonstrate practical SQL
skills by analyzing customer, order, product, and sales data.

The analysis answers business-related questions about customer spending,
orders, products, sales, payment methods, and product categories.

---

## Dataset

This project uses a synthetic e-commerce dataset created for SQL
practice and portfolio development.

The dataset contains several related tables representing different
parts of an e-commerce business, including customers, products,
orders, and order items.

### Main Tables

- `customers` – contains customer information
- `products` – contains product information
- `orders` – contains customer order information
- `order_items` – contains the individual products included in orders
- `employees` – contains employee information

---

## Objectives

The main objective of this project is to use SQL to extract meaningful
information from relational e-commerce data.

The analysis includes questions such as:

- How many orders are associated with each payment method?
- Which payment methods are used most frequently?
- What are the total sales for each product category?
- Which customers have spent the most money?
- How many orders has each customer placed?
- What is the total amount spent by each customer?
- Which products contribute the most to sales?
- How can customer and order information be combined using SQL joins?

---

## Tools Used

- SQL
- MySQL
- GitHub

---

## SQL Concepts Demonstrated

This project demonstrates the following SQL concepts:

### Basic SQL

- `SELECT`
- `WHERE`
- `ORDER BY`
- `LIMIT`
- Column aliases

### Aggregate Functions

- `COUNT()`
- `SUM()`
- `AVG()`
- `MIN()`
- `MAX()`

### Grouping

- `GROUP BY`
- Aggregate calculations

### Joins

- `INNER JOIN`
- `LEFT JOIN`

### Calculated Fields

Examples include:

```sql
quantity * unit_price
