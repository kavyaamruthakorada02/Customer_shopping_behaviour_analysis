# Customer_shopping_behaviour_analysis
Data Analysis project showcasing Customer_shopping_behaviour_analysis using python, SQL and powerBi

# Customer Shopping Behavior Analysis

## Overview

An end-to-end data analytics project analyzing customer shopping behavior using **Python, SQL Server, and Power BI**.

The project covers data cleaning, exploratory data analysis, SQL-based business analysis, customer segmentation, and interactive dashboard development.

### Workflow

**CSV → Python → Data Cleaning & EDA → SQL Server → SQL Analysis → Power BI**

---

## Dataset

The dataset contains **3,900 customer records** with information about:

- Customer demographics
- Products and categories
- Purchase amounts
- Discounts and subscriptions
- Shipping methods
- Review ratings
- Previous purchases
- Purchase frequency

---

## Tools & Technologies

- **Python / Pandas** – EDA, data cleaning & feature engineering
- **SQL Server** – Data storage and business analysis
- **Power BI** – Interactive dashboard and visualization
- **SQLAlchemy / PyODBC** – Python to SQL Server connection
- **Gamma** – Project presentation

---

## Python – Data Preparation

The Python script performs:

- Dataset loading and EDA
- Missing-value analysis
- Missing `Review Rating` handling using category-level median
- Column name standardization
- Age-group creation
- Purchase-frequency transformation
- Removal of redundant columns
- Loading cleaned data into SQL Server

---

## SQL Analysis

SQL Server was used to answer business questions such as:

- Revenue by gender
- Discounted customers spending above average
- Top-rated products
- Standard vs Express shipping spending
- Subscriber vs non-subscriber analysis
- Products with the highest discount rate
- New, Returning, and Loyal customer segmentation
- Top 3 products within each category
- Subscription behavior of repeat customers
- Revenue contribution by age group

### SQL Concepts

`GROUP BY` • `CASE` • `Subqueries` • `CTEs` • `Aggregate Functions` • `Window Functions` • `ROW_NUMBER()` • `PARTITION BY`

---

## Power BI Dashboard

The Power BI dashboard provides an interactive view of:

- Customer demographics
- Revenue and purchase behavior
- Product performance
- Discounts
- Subscription status
- Customer segments
- Age-group analysis


---

## Key Insights

The analysis helps identify:

- Revenue patterns across customer groups
- Product performance and customer ratings
- Discount and purchasing behavior
- Subscription and repeat-purchase patterns
- Customer loyalty segments
- Revenue contribution across age groups


