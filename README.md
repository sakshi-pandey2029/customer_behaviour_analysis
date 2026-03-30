# customer_behaviour_analysis
An end-to-end customer shopping behavior analysis project using SQL, Python, and Power BI to segment customers, analyze purchasing patterns, and build an interactive dashboard for data-driven business insights.

# 📌 Project Overview

This project analyzes customer shopping behavior using SQL and Power BI to generate meaningful business insights. The objective is to understand customer segments, purchasing patterns, and behavioral trends to support data-driven decision-making.

## The project includes:

1. Data cleaning and transformation
2. SQL-based customer segmentation
3. Exploratory data analysis
4. Interactive Power BI dashboard

## 📂 Project Files

Customer_shopping_behavior.csv → Raw dataset

Customer_Behaviour_query.sql → SQL queries for data transformation & segmentation

Customer_behavior_dashboard.pbix → Power BI dashboard file

Youtube_project.ipynb → Jupyter Notebook for additional analysis

## 🧾 Dataset Description

The dataset contains customer-level shopping information including:

Customer ID

Age

Gender

Category

Purchase Amount

Previous Purchases

Payment Method

Location

Review Rating

## 🛠️ Tools & Technologies Used

SQL – Data cleaning, transformation, segmentation

Power BI – Dashboard development & visualization

Python (Pandas, Matplotlib, Seaborn) – Exploratory Data Analysis

Excel/CSV – Data source format

# 📊 Key Analysis Performed
## 1️⃣ Customer Segmentation

Customers were categorized based on previous purchases:

CASE 
    WHEN previous_purchases = 1 THEN 'New'
    WHEN previous_purchases BETWEEN 2 AND 10 THEN 'Returning'
    ELSE 'Loyal'
END AS customer_segment
## 2️⃣ KPI Analysis

Total Revenue

Average Purchase Amount

Customer Distribution by Segment

Category-wise Sales

Gender-wise Spending Analysis

## 3️⃣ Behavioral Insights

High-value customer identification

Spending trends across age groups

Most preferred payment methods

Product category performance

## 📈 Dashboard Features (Power BI)

Interactive slicers for filtering

Segment-wise customer distribution

Revenue trends visualization

Category performance charts

Demographic analysis

## 🚀 How to Use

Download the repository.

Open the .pbix file in Power BI Desktop.

Run the SQL queries in your SQL environment (MySQL/SQL Server).

Use the CSV file as the dataset source if needed.

## 💡 Key Business Insights

Loyal customers contribute significantly to total revenue.

Certain categories generate higher repeat purchases.

Returning customers form the majority of the customer base.

Payment preference trends can help optimize checkout strategies.

## 🎯 Project Objective

To build an end-to-end customer behavior analytics solution that demonstrates:

Data cleaning & transformation

SQL querying skills

Data modeling

KPI development using DAX

Dashboard storytelling

## 📌 Author

Sakshi Pandey

Aspiring Data Analyst

Skilled in SQL, Power BI, Excel & Python
