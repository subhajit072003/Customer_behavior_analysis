
# 🛍️ Customer Shopping Behavior Analysis Dashboard

# End-to-End Customer Analysis using Python, SQL & Power BI

A visually rich and business-focused analytics project designed to analyze customer shopping behavior, identify purchasing patterns, understand subscription and discount behavior, and deliver actionable insights through an interactive Power BI dashboard.

# Purpose

The Customer Shopping Behavior Dashboard is an end-to-end data analytics solution built to transform raw customer transaction data into meaningful business insights.

By combining Python for data cleaning and transformation, SQL for analytical querying, and Power BI for visualization, this project helps stakeholders understand customer behavior, product performance, revenue contribution, and purchasing patterns.

# 🧰 Tech Stack

The project was built using the following tools and technologies:

🐍 Python / Pandas – Data cleaning, transformation, and feature engineering

🗄️ PostgreSQL – Database storage and SQL analysis

🧮 SQL – KPI calculations, customer segmentation, ranking, and business analysis

📊 Power BI Desktop – Interactive dashboard and data visualization

📓 Jupyter Notebook – Data preparation and analysis workflow

📁 File Formats – .csv (dataset), .sql (queries), .ipynb (analysis), .pbix (dashboard), .png (preview)

# Business Problem

Retail businesses collect large amounts of customer transaction data, but raw data alone does not provide a clear understanding of customer behavior.

Important business questions include:

Which customer groups generate the most revenue?

Do subscribed customers spend differently from non-subscribers?

Which products have the highest ratings and sales?

Which products have the highest discount usage?

How does purchasing behavior vary across different age groups?

Are repeat customers more likely to subscribe?

Answering these questions directly from raw data can be time-consuming and difficult.

# 🎯 Goal of the Dashboard

The primary goal of this dashboard is to:

Deliver a clear and interactive overview of customer behavior

Analyze revenue and sales across product categories

Understand subscription and discount patterns

Identify purchasing trends across different age groups

Compare customer behavior across different shipping methods

Support data-driven decisions related to customers, products, and sales

# 📊 Dataset Overview

The dataset contains:

Total Customers: 3,900

Total Columns: 18

Duplicate Records: 0

Missing Review Ratings: 37

The missing review ratings were handled using the median rating of the respective product category.

Additional features such as Age Group and Purchase Frequency in Days were created during the data preparation process.

# 📈 Walkthrough of Key Visuals

## Key Performance Indicators

Total Customers: 3.9K

Average Purchase Amount: $59.76

Average Review Rating: 3.75

These KPIs provide a quick overview of the overall customer base and purchasing behavior.

# Subscription Analysis

The dashboard shows the distribution of customers based on subscription status.

Non-Subscribers: 73%

Subscribers: 27%

This helps understand the current distribution of subscribed and non-subscribed customers.

# Category-Wise Sales & Revenue

The dashboard compares sales and revenue across:

Clothing

Accessories

Footwear

Outerwear

Clothing records the highest revenue and sales among the displayed categories.

This analysis helps identify the major product categories contributing to overall performance.

# Age Group Analysis

Customer behavior is analyzed across different age groups:

Young Adult

Adult

Middle-aged

Senior

The dashboard compares both revenue and sales across these groups to identify differences in purchasing behavior.

# 🔍 SQL Analysis Highlights

SQL was used extensively to:

Calculate revenue by gender

Compare subscriber and non-subscriber spending

Identify top-rated products

Analyze discount usage

Compare Standard and Express shipping

Segment customers into New, Returning, and Loyal

Find the top 3 products within each category

Analyze repeat buyers and subscription status

Calculate revenue contribution by age group

SQL concepts used include:

`GROUP BY`

`SUM()`

`AVG()`

`COUNT()`

`CASE WHEN`

Subqueries

CTEs

Window Functions

`ROW_NUMBER()`

`PARTITION BY`

All analytical SQL queries are included in the repository for transparency and reproducibility.

# 🚀 Business Insights

The analysis provides visibility into:

Customer subscription distribution

Revenue and sales contribution by product category

Purchasing behavior across different age groups

Discount usage across products

Customer segmentation based on previous purchases

Repeat purchasing and subscription behavior

Product ratings and purchasing patterns

The dashboard provides a consolidated view that can support customer, product, marketing, and sales analysis.

# 📊 Dashboard Preview

<img width="1142" height="761" alt="image" src="https://github.com/user-attachments/assets/1ff808fb-d4b7-4137-8766-63c4431fefed" />


# 📁 Project Structure

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
````

# How to Use This Project

1. Review the dataset and Jupyter Notebook to understand the data cleaning and transformation process.
2. Explore the SQL queries to understand the business questions and analytical logic.
3. Open the Power BI dashboard (`.pbix` file) to interact with the visuals.
4. Use the available slicers to analyze customer behavior by subscription status, gender, category, and shipping type.

```

