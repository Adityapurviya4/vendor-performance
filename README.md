## ✅ Vendor Performance Analysis Project
## 1. Introduction & Project Overview

This project delivers an end-to-end Vendor Performance Analysis System designed to help businesses identify high-performing and low-performing vendors, optimize purchasing decisions, reduce unsold inventory, and improve profit margins.

Using SQL for data engineering, Python for analytical modeling, and Power BI for business intelligence, the project replicates how real companies manage and evaluate vendor contributions.

## 2. Understanding the Project Flow

The workflow (as shown in the image) follows a complete data analytics lifecycle:

Define Business Problem

Explore Database → Merge & Clean Data (SQL)

Generate Aggregated Table

Load table into Jupyter Notebook

EDA + Hypothesis Testing (Python)

Save processed table back to database

Create Interactive Dashboard (Power BI)

Write Insights & Final Report

This simulates production-grade analytics pipelines used in organizations.

## 3. Understanding the Business Problem

Companies work with multiple vendors for purchases and product supply.
Key business questions answered:

Which vendors contribute the most to sales?

Which brands generate the highest profit?

Are there vendors with high purchases but low sales?

How to reduce unsold capital tied to non-moving products?

What is the overall vendor performance distribution?

Outcome: Better vendor negotiations, optimized purchasing, and improved profitability.

## 4. SQL Data Analysis & Cleaning

Key tasks performed:

Import and explore raw sales, vendors, and purchase tables

Data quality checks (duplicates, missing values, invalid entries)

Joins across multiple operational tables

Calculation of metrics:

Total Sales Dollars

Total Purchase Dollars

Gross Profit

Profit Margin

Unsold Capital

Aggregated table creation for downstream EDA and BI

Store cleaned and aggregated data back into the database

## 5. Exploratory Data Analysis in Python

Using Pandas, Matplotlib, Seaborn, the analysis covered:

✔ Trend & Distribution Analysis
✔ Outlier Detection
✔ High vs Low Performing Vendors
✔ Purchase vs Sales Correlation
✔ Brand-level profitability patterns

Data visualizations included:

Sales vs Purchase scatterplots

Vendor turnover distribution

Profit margin boxplots

Contribution pie charts

Unsold capital trends

## 6. Hypothesis Testing & Confidence Intervals

Examples:

H0: High-purchase vendors do not necessarily generate higher sales

H1: High-purchase vendors generate significantly higher sales

Statistical methods:

2-sample t-test

Chi-square test for categorical relationships

95% Confidence intervals for vendor performance scores

Outcome:
✔ Statistically significant difference found → High-purchase vendors do bring higher sales on average.

## 7. Power BI Dashboard Walkthrough

Power BI dashboard sections:

### 🔹 KPI Cards

Total Sales Dollars

Total Purchase Dollars

Gross Profit

Avg Profit Margin

Unsold Capital

### 🔹 Visuals

Vendor Purchase Contribution Donut Chart

Top Vendors by Sales / Profit

Top Brands by Sales

Low Performing Vendors / Brands

Dynamic filters for vendor, brand, region, year

Dashboard enables decision makers to quickly identify revenue drivers and inefficiencies.

## 8. Report Writing – Business Insights

The final report summarizes:

Key revenue-generating vendors

Underperforming vendors needing renegotiation

Brands contributing the highest gross profit

Vendors with largest unsold inventory

Recommendations to optimize purchases and reduce losses
