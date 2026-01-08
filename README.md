# Pizza Sales Analysis Using SQL

## Project Overview

This project focuses on analyzing pizza sales data using **pure SQL** to extract meaningful business insights from a relational database. The analysis answers real-world business questions related to sales performance, customer ordering behavior, revenue trends, and product performance.

The project demonstrates strong fundamentals in **SQL querying, joins, aggregations, subqueries, and window functions**, making it suitable for **Data Analyst / Business Analyst** roles.

---

## Problem Statement

In the food and restaurant industry, large volumes of transactional data are generated daily. However, raw data alone does not provide actionable insights unless it is properly analyzed.

The objective of this project is to:

* Analyze pizza sales data stored across multiple relational tables
* Understand overall sales performance and revenue generation
* Identify top-selling and high-revenue pizza types
* Analyze customer ordering patterns by time, category, and size
* Perform cumulative and percentage-based revenue analysis

All analysis is performed **exclusively using SQL**, without the use of any BI or visualization tools.

---

## Dataset Description

The dataset consists of four relational tables:

### 1️⃣ orders

* `order_id` – Unique identifier for each order
* `order_date` – Date of the order
* `order_time` – Time of the order

### 2️⃣ order_details

* `order_details_id` – Unique identifier for order line items
* `order_id` – Foreign key referencing orders table
* `pizza_id` – Foreign key referencing pizzas table
* `quantity` – Number of pizzas ordered

### 3️⃣ pizzas

* `pizza_id` – Unique pizza identifier
* `pizza_type_id` – Foreign key referencing pizza_types table
* `size` – Pizza size (S, M, L, XL, etc.)
* `price` – Price of the pizza

### 4️⃣ pizza_types

* `pizza_type_id` – Unique pizza type identifier
* `name` – Pizza name
* `category` – Pizza category (Classic, Supreme, Chicken, Veggie)
* `ingredients` – Ingredients used

---

## Tools & Technologies

* **SQL (MySQL)** – Data querying and analysis
* **Relational Database** – Structured data storage
* **CSV Files** – Source data import

---

## Key Business Questions Answered

### Basic Analysis

* Total number of orders placed
* Total revenue generated from pizza sales
* Highest-priced pizza
* Most commonly ordered pizza size
* Top 5 most ordered pizza types

### Intermediate Analysis

* Total quantity sold by pizza category
* Distribution of orders by hour of the day
* Category-wise distribution of pizzas
* Average number of pizzas ordered per day
* Top 3 pizza types based on revenue

### Advanced Analysis

* Percentage contribution of each pizza category to total revenue
* Cumulative revenue generated over time
* Top 3 revenue-generating pizzas within each category using window functions

---

## SQL Concepts Used

* `INNER JOIN`
* `GROUP BY` and `HAVING`
* Aggregate functions (`SUM`, `COUNT`, `AVG`)
* Subqueries
* Window functions (`RANK()`, `SUM() OVER()`)
* Date and time functions

---

## Key Insights

* Over **21,000+ orders** were analyzed to evaluate sales performance
* Pizza sales generated **$800K+ in total revenue**
* Large-sized pizzas were the most frequently ordered
* Classic category contributed the highest quantity sold
* Clear daily and hourly ordering patterns were identified

---

## Project Outcome

This project highlights how **SQL alone** can be used to:

* Perform end-to-end data analysis
* Derive actionable business insights
* Support decision-making related to pricing, inventory, and product strategy

It demonstrates strong foundational skills required for **Data Analyst and Business Analyst** roles.

---

## How to Use This Repository

* Review SQL queries to understand problem-solving approach
* Use the dataset to practice SQL joins and analytical queries
* Extend the project by creating dashboards using Power BI or Tableau

---

## Author

**Kuldeep Vishwakarma**

---

