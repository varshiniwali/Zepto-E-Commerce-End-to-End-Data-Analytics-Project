# Zepto-E-Commerce-End-to-End-Data-Analytics-Project
End-to-end Zepto E-commerce analytics project across 4 tables. Excel reporting with Pivot Tables &amp; Slicers, 30+ SQL queries using Joins, Group By, Having, Subqueries &amp; Window Functions, Python EDA with Pandas, Seaborn &amp; Matplotlib for insights, plus interactive Power BI dashboard with DAX KPIs tracking sales, AOV and delivery performance for growth

# 🛒 Zepto E-Commerce - End-to-End Data Analytics Project

> End-to-end analytics project analyzing Zepto sales, customer behavior, and delivery performance across 4 tables using Excel, SQL, Python, and Power BI.

![Excel](https://img.shields.io/badge/Excel-Pivot%20%7C%20Slicers%20%7C%20Dashboard-green)
![SQL](https://img.shields.io/badge/SQL-30%2B%20Queries-blue)
![Python](https://img.shields.io/badge/Python-Pandas%20%7C%20Seaborn%20%7C%20Matplotlib-yellow)
![PowerBI](https://img.shields.io/badge/PowerBI-DAX%20%7C%20Dashboard-orange)

### 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Tech Stack & Workflow](#-tech-stack--workflow)
- [Project Structure](#-project-structure)
- [Key Insights](#-key-insights)
- [Dashboard Preview](#-dashboard-preview)
- [How to Run](#-how-to-run-this-project)

### 📖 Project Overview
This project analyzes Zepto's quick-commerce operations to answer critical business questions like sales trends, top-selling categories, customer retention, and delivery delays. The entire workflow from data cleaning to business storytelling is covered.

**Business Questions Solved:**
1. What are the top 5 selling products and categories?
2. Which city generates the highest revenue and orders?
3. What is the average delivery time and where do delays occur?
4. Who are the most valuable customers (RFM)?
5. Month-on-Month and Year-on-Year sales growth.

### 🗂️ Dataset
The project uses 4 normalized tables:

1.  **Customers:** customer_id, customer_name, city, signup_date
2.  **Products:** product_id, product_name, category, price
3.  **Orders:** order_id, customer_id, product_id, quantity, order_date, total_amount
4.  **Delivery:** delivery_id, order_id, delivery_time_mins, delivery_status

### 🛠️ Tech Stack & Workflow

**1. Excel - Reporting & Cleaning**
- Data cleaning, removing duplicates
- Pivot Tables, Pivot Charts
- Slicers & Timeline for interactive report
- Final sales dashboard

**2. SQL (MySQL) - 30+ Business Queries**
- `01_schema_creation.sql` - Created 4 tables with Primary/Foreign Keys
- `02_business_queries.sql` - Divided into:
    - Basic Aggregation: `GROUP BY, HAVING`
    - Joins: `INNER, LEFT JOIN` across 4 tables
    - Subqueries
    - Window Functions: `RANK(), DENSE_RANK(), ROW_NUMBER(), LAG(), LEAD()

**3. Python - EDA & Visualization**
- `Zepto_EDA.ipynb`
- Data manipulation with **Pandas**
- Visualizations with **Matplotlib & Seaborn**
- Analysis: Sales trend, Category performance, City-wise analysis, Delivery time analysis

**4. Power BI - Dashboard & DAX**
- Interactive KPI Dashboard
- **DAX Measures Created:** Total Sales, Total Orders, AOV, Avg Delivery Time, YTD Sales
- Features: Drill-through, Slicers for City/Category

### 📁 Project Structure
