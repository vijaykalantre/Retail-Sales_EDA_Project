#Retail Sales Data Cleaning & Exploratory Data Analysis (EDA)
# Project Overview

This project focuses on cleaning, analyzing, and visualizing a highly messy retail sales dataset using Python.
The goal is to transform raw, unreliable data into meaningful business insights through structured data cleaning and Exploratory Data Analysis (EDA).

The dataset contains 50,000+ records with real-world data quality issues such as missing values, duplicates, inconsistent text, invalid dates, extreme outliers, and incorrect revenue calculations.

# Objectives

Clean and preprocess messy retail sales data

Handle missing values, duplicates, and outliers

Perform Univariate, Bivariate, and Multivariate analysis

Generate actionable business insights

Create meaningful visualizations for decision-making

# Data Cleaning Highlights

✔ Standardized text data (city, category, product, etc.)
✔ Fixed mixed and invalid date formats
✔ Removed duplicate order IDs
✔ Filtered invalid and negative quantities
✔ Detected and treated price outliers using IQR
✔ Validated discount percentages (0–100%)
✔ Recalculated final unit price and revenue

# Exploratory Data Analysis (EDA)

The analysis is divided into clear sections:

Descriptive Analysis – Revenue, orders, products, and categories

Time-Based Analysis – Monthly trends, seasonality, quarters, weekdays vs weekends

Customer Behavior – New vs returning customers, loyalty, discounts

Pricing & Discount Insights – Discount impact on revenue and margins

Geographic Insights – City and region performance

Outliers & Anomaly Detection – High-value orders and suspicious transactions

# Analysis Types

Univariate Analysis – Individual variable distributions and anomalies

Bivariate Analysis – Relationships between pairs of variables

Multivariate Analysis – Combined impact of price, quantity, discount, customer type, city, and sales channel

# Key Business Insights

Returning customers generate higher revenue per transaction

Revenue is concentrated in a few top-performing cities

Discounts have weak impact on increasing revenue

Online sales channel contributes significantly to total revenue

Revenue is driven more by quantity and unit price than heavy discounts

# Tools & Technologies

Python

Pandas & NumPy – Data cleaning & manipulation

Matplotlib & Seaborn – Data visualization

Jupyter Notebook / Python Scripts
