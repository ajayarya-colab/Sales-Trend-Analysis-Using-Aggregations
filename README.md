# Task 6: Sales Trend Analysis Using Aggregations

## 📌 Project Overview
This project focuses on time-series sales trend analysis using structured SQL aggregations. The primary objective is to evaluate monthly performance metrics, specifically looking at total financial revenue and order fulfillment volumes over time.

## 🛠️ Technology Stack
* **Environment:** Google Colab (.ipynb)
* **Database Engine:** SQLite3
* **Data Processing & Visualization:** `pandas`, `matplotlib`, `seaborn`

## ⚙️ SQL Dialect Adaptation Note
While standard enterprise databases like PostgreSQL or MySQL utilize the `EXTRACT(MONTH FROM order_date)` statement, **SQLite** uses the highly efficient `strftime('%m', order_date)` string-formatting function to isolate month-level temporal markers. 

## 🔍 Core Insights
* **Revenue Drivers:** Financial revenue peaked dramatically towards mid-year (Month 06), demonstrating strong positive growth vectors.
* **Volume Stability:** Order volume remained consistently stable across periods, indicating that total revenue growth was primarily driven by higher average transaction values per order rather than an increase in transaction counts.
