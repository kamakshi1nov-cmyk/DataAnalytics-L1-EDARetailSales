# Retail Sales Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset using Python. The objective is to understand sales performance, customer purchasing behavior, product category performance, and sales trends.

## Objectives

- Analyze overall retail sales performance
- Identify the best-performing product categories
- Analyze customer purchasing behavior
- Compare sales by gender
- Analyze sales across different age groups
- Identify monthly sales trends
- Calculate important business KPIs

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains 1,000 retail transactions with information about:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

## Data Preparation

The following steps were performed:

- Checked for missing values
- Checked for duplicate records
- Converted the Date column to datetime format
- Created customer age groups
- Performed descriptive statistical analysis

## Exploratory Data Analysis

The following analyses were performed:

1. Total sales by product category
2. Sales by gender
3. Monthly sales trend
4. Sales by age group
5. Sales by product category and gender
6. Top customers by spending
7. Quantity sold by product category
8. Average transaction value by product category

## Key Findings

- **Total Sales:** ₹456,000
- **Total Quantity Sold:** 2,514 units
- **Unique Customers:** 1,000
- **Average Transaction Value:** ₹456
- **Highest Revenue Category:** Electronics — ₹156,905
- **Highest Quantity Category:** Clothing — 894 units
- **Highest Sales Gender:** Female — ₹232,840
- **Highest Sales Age Group:** 46–55 — ₹100,690
- **Highest Sales Month:** May 2023 — ₹53,150

## Business Insights

Electronics generated the highest overall revenue, while Clothing recorded the highest number of units sold. Female customers contributed slightly higher sales than male customers. The 46–55 age group generated the highest sales among the analyzed age groups.

These insights can help retailers understand customer segments, evaluate product performance, identify sales trends, and support data-driven business decisions.

## Project Files

- `EDA_Retail_Sales.ipynb` — Jupyter Notebook containing the complete analysis
- `retail_sales_dataset.csv` — Retail sales dataset

## Conclusion

This project demonstrates how Python-based exploratory data analysis can be used to transform raw retail transaction data into meaningful business insights through data cleaning, statistical analysis, and visualization.