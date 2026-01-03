# 📊 Customer Shopping Behavior Analysis
## 📌 Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, product performance, and subscription behavior.
The analysis combines Python, SQL (MySQL), and Power BI to deliver end-to-end data analytics from raw data to executive-ready insights and visual dashboards.

## 📂 Dataset

Source: Customer shopping transaction dataset

Records: 3,900 purchases

Features:

Customer demographics (age, gender, location, subscription status)

Purchase details (category, item, amount, season, size, color)

Shopping behavior (discounts, ratings, shipping type, purchase frequency)

Data Issues:

Missing values in review ratings

Redundant columns handled during cleaning

## 🛠 Tools & Technologies

Python: Pandas

SQL: MySQL

BI & Visualization: Power BI

Reporting & Presentation: Gamma (PPT)

Others: Jupyter Notebook, MySQL Workbench

## 🔄 Project Workflow / Steps
### 1️⃣ Data Loading (Python)

Loaded raw dataset using Pandas

Performed initial inspection (info(), describe())

### 2️⃣ Exploratory Data Analysis (EDA)

Analyzed distributions, trends, and outliers

Identified spending patterns by gender, age group, and category

Studied discount usage and subscription behavior

### 3️⃣ Data Cleaning & Preparation

Handled missing review ratings using median imputation

Standardized column names (snake_case)

Removed redundant columns

Created derived features such as:

Age groups

Customer segments (New, Returning, Loyal)

### 4️⃣ SQL Analysis (MySQL)

Loaded cleaned data into MySQL

Executed business-focused SQL queries, including:

Revenue by gender and age group

Subscriber vs non-subscriber performance

Top-rated and top-selling products

Discount impact on revenue

Shipping type comparison

Customer segmentation analysis

### 5️⃣ Dashboard Development (Power BI)

Built an interactive dashboard with:

KPI cards (Revenue, Avg Spend, Customers)

Category and product-level analysis

Subscription and discount insights

Filters for dynamic exploration

### 6️⃣ Reporting & Presentation

Created a structured analytical report

Designed a professional presentation (PPT) using Gamma

Focused on insights, trends, and business recommendations

## 📈 Dashboard

The Power BI dashboard provides:

Executive-level KPIs

Customer segmentation insights

Product and category performance

Discount and subscription impact analysis

📌 Screenshots of the dashboard are included in the repository.

## 📊 Key Results & Insights

Subscribers generate higher average revenue than non-subscribers

Loyal customers contribute a significant share of total revenue

Certain products rely heavily on discounts for sales volume

Express shipping users show higher average purchase value

Specific age groups drive the majority of revenue

## ▶️ How to Run This Project
Python Analysis
pip install pandas mysql-connector-python


Open the Jupyter Notebook

Run cells sequentially for EDA and data cleaning

SQL Analysis

Import the cleaned dataset into MySQL

Run SQL scripts provided in the sql/ folder using MySQL Workbench

Power BI Dashboard

Open the .pbix file in Power BI Desktop

Refresh data connection if required

## 📌 Business Value

This project demonstrates how raw customer data can be transformed into actionable business insights using a modern analytics stack.
It reflects real-world analytics workflows commonly used in data analyst roles.

👤 Author

Divya Vaddam
Aspiring Data Analyst | Python | SQL | Power BI
