# Retail Customer Analytics

## Project Overview

This project analyzes retail transaction data to understand customer purchasing behavior using RFM analysis, retention analysis, and churn analysis.

The main objective of this project is to identify loyal customers, detect churned customers, analyze customer retention patterns, and provide business recommendations to improve customer retention and long-term revenue.

---

## Business Problem

Retail businesses need to understand customer behavior in order to maintain customer loyalty and reduce customer churn.

By analyzing transaction data, businesses can:
- Identify high-value customers
- Detect inactive customers
- Understand customer purchasing behavior
- Improve customer retention strategies
- Increase long-term business revenue

---

## Dataset Information

The dataset contains retail transaction data with 240 rows and 10 columns.

### Dataset Columns

| Column | Description |
|---|---|
| Transaction ID | Unique transaction identifier |
| Date | Transaction date |
| Product Category | Product category |
| Product Name | Product name |
| Units Sold | Number of units sold |
| Unit Price | Product price per unit |
| Region | Customer region |
| Payment Method | Payment method used |
| Customer ID | Unique customer identifier |
| Age | Customer age |

### Additional Feature Engineering

A new column called `Total Revenue` was created using:

```python
Total Revenue = Units Sold × Unit Price
