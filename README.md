
# Customer Shopping Behavior Analysis

An end-to-end data analytics project analyzing customer shopping behavior using **Python, SQL, PostgreSQL, and Power BI**.

## 📌 Project Overview

This project analyzes **3,900 customer records** to understand purchasing patterns, customer segments, product performance, subscription behavior, discounts, shipping methods, and revenue.

### 🔧 Tools Used

- **Python (Pandas)** – Data cleaning & transformation
- **PostgreSQL** – Database & SQL analysis
- **SQL** – Business problem solving
- **Power BI** – Interactive dashboard

## 🔄 Project Workflow

```text
Raw Data
   ↓
Python / Pandas
   ↓
Data Cleaning & Transformation
   ↓
PostgreSQL
   ↓
SQL Analysis
   ↓
Power BI Dashboard
````

## 🐍 Python

Performed:

* Data cleaning and inspection
* Missing value treatment
* Column standardization
* Age group creation
* Purchase frequency transformation
* Data preparation for SQL

Missing `Review Rating` values were handled using the median rating of the respective product category.

## 🗄️ SQL Analysis

The project answers 10 business questions, including:

* Revenue by gender
* Customers spending above average with discounts
* Top-rated products
* Standard vs. Express shipping spending
* Subscriber vs. non-subscriber spending
* Products with highest discount rates
* New, Returning and Loyal customer segmentation
* Top 3 products within each category
* Repeat buyers and subscription behavior
* Revenue by age group

SQL concepts used include **CTEs, subqueries, CASE statements, aggregations, and window functions**.

## 📊 Power BI Dashboard

The dashboard includes:

* **3.9K** Customers
* **$59.76** Average Purchase Amount
* **3.75** Average Review Rating
* Subscription Status analysis
* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Sales by Age Group
* Interactive filters for Gender, Category, Subscription Status and Shipping Type

![Customer Behavior Dashboard](images/dashboard.png)

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebook/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── dashboard/
│   └── Customer_Behavior_Dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
```

## 💡 Key Insights

* Non-subscribers represent approximately **73%** of customers.
* Subscribers represent approximately **27%** of customers.
* **Clothing** generates the highest revenue and sales among the displayed categories.
* Customer revenue and sales vary across different age groups.
* The analysis provides insights into discount usage, repeat purchasing and subscription behavior.

## 🎯 Skills Demonstrated

**Python | Pandas | SQL | PostgreSQL | Power BI | Data Cleaning | Data Analysis | Customer Segmentation | Data Visualization**

## 👨‍💻 Author

**Your Name**

[LinkedIn](https://www.linkedin.com/in/your-profile) • [GitHub](https://github.com/yourusername)

```

This is the version I'd recommend for your portfolio: **professional, readable, and detailed enough for a recruiter without making them scroll through a huge README.**
```
