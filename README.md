# 🛒 Customer Trends Data Analysis

SQL • Python • Power BI

Turning raw customer data into meaningful business insights 📊

## 📝 Project Overview

This project explores customer shopping behavior to uncover trends related to spending, subscriptions, discounts, products, and demographics.

Using SQL for deep analysis, Python for data handling, and Power BI for visualization, this project demonstrates an end-to-end data analytics workflow: from raw data to business-ready insights.

### 🛠️ Tools & Technologies

MySQL – Data storage and querying

SQL – Business analysis (aggregations, CTEs, subqueries, window functions)

Python – Data loading & validation (Pandas, SQLAlchemy)

Power BI – Interactive dashboards & KPIs

Git & GitHub – Version control & project sharing

### 📂 Dataset

The dataset contains customer shopping information including:

Customer demographics (age, gender)

Purchase details (amount, product, category)

Subscription status

Discount usage

Review Ratings

Shipping type

## ❓ Business Questions Answered

This project answers real-world questions such as:

💰 Do subscribed customers spend more than non-subscribers?

🧾 How do discounts impact high-value purchases?

⭐ Which products have the highest average review ratings?

👥 How does revenue vary across age groups and gender?

📦 Which categories generate the most sales and revenue?

🔁 Are repeat buyers more likely to subscribe?

### 🧮 SQL Analysis Highlights

Revenue analysis by gender, age group, and subscription status

Customer segmentation (New, Returning, Loyal)

Product-level performance analysis

Discount impact measurement

Use of CTEs, subqueries, CASE statements, and window functions

📄 File: customer_behavior_sql_queries.sql


### ✏️ SQL Column Naming
For readability and best practices, SQL queries use standardized
snake_case column names. These are logically mapped from the original
CSV columns (e.g., `Purchase Amount (USD)` → `purchase_amount`).


🐍 Python Usage

Python was used to:

Load data into MySQL

Validate SQL results

Perform exploratory analysis

📓 Notebook: Customer_Shopping_Behavior_Analysis.ipynb

## 📊 Power BI Dashboard

An interactive dashboard was created to visualize key insights, including:

KPI cards (Total Customers, Avg Spend, Avg Rating)

Revenue & sales by category

Subscription-based analysis

Age group and demographic insights

Dynamic filters for deeper exploration

📎 File: customer_behavior_dashboard.pbix

Download and open using Power BI Desktop

## 📊 Power BI Dashboard Preview

### Dashboard Overview
![Dashboard Overview](screenshots/dashboard_overview.png)

## 🚀 Key Insights

📈 Subscribed customers spend more on average

👕 Clothing category generates the highest revenue

🎯 Young adults contribute the most to total sales

🏷️ Discounts do not always mean lower spending

## ▶️ How to Run the Project

Load the dataset into MySQL

Run the SQL queries provided

Open the Python notebook for analysis

Open the Power BI .pbix file and refresh data

## 👩‍💻 Author

Diya
| Data Analytics Enthusiast | SQL • Python • Power BI

🔗 GitHub: https://github.com/DIYAD286
