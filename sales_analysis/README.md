#  Sales Performance Analysis (Jan–Mar 2019)

This project presents a detailed analysis of retail sales performance using transaction data from January to March 2019. The goal is to uncover trends, evaluate product and regional performance, understand customer behavior, and provide actionable recommendations to improve sales strategy.

>  Tools Used: **MySQL Workbench** (for data cleaning & transformation), **Excel** (for analysis & visualization)

---

##  1. Project Overview

- **Objective**: Identify top-performing products, cities, branches, and customer segments.
- **Scope**: Analyze revenue, profit margins, payment methods, and sales trends over time.
- **Data Source**: Transactional sales data extracted from a MySQL database and exported as individual tables.

---

##  2. Data Extraction & Transformation

### 2.1 Key Fields
- Invoice ID, Branch, City, Customer Type, Gender, Product Line
- Unit Price, Quantity, Tax, Total Price, Date, Time, Payment Method
- Cost of Goods Sold (COGS), Gross Income, Rating

### 2.2 MySQL Data Processing
- **Date & Time Formatting**: `STR_TO_DATE()`, `TIME_FORMAT()` for consistency
- **Revenue & Profit Metrics**: Calculated total revenue, gross profit, and profit margin
- **Aggregations**: Sales grouped by product line, branch, customer type
- **Customer Segmentation**: Analysis by gender and customer type
- **Time-Based Trends**: Hourly patterns and payment preferences

---

##  3. Data Analysis & Excel Visualizations

### 3.1 Key Metrics
- **Total Transactions**
- **Total Sales Revenue**
- **Average Transaction Value**
- **Gross Profit & Profit Margin**

### 3.2 Visual Insights

####  Product Line Performance

- **Insight**: *Electronic Accessories* dominated sales, while *Fashion Accessories* yielded high profit margins.

#### 🏢 Branch & City Performance

- **Insight**: *Branch C * had the highest revenue; *Branch B* underperformed.

#### 👥 Customer Segmentation

- **Insight**: *Members* drove volume; *Normal* customers had higher avg. transaction values.

####  Time-Based Sales

- **Insight**: Peak sales occurred between **1 PM – 4 PM**.

####  Payment Preferences

- **Insight**: *E-wallet* were the preferred mode of payment.

---

##  4. Key Insights & Recommendations

###  Insights
- **Electronic Accessories** = highest sales; **Food & Beverages** = strong engagement.
- Sales spike during **afternoon hours**.
- **Digital payments** are now the norm.
- **Branch C** leads in revenue, indicating operational excellence or favorable demographics.

### Recommendations
- **Optimize Inventory** for top-performing categories.
- **Study & Replicate Branch C**’s strategies in other regions.
- **Afternoon Discounts** to maximize peak-time sales.
- **Loyalty Programs** to convert Normal customers into Members.

---

## Summary

This project demonstrates end-to-end data analysis — from SQL-based transformation to Excel dashboards — and provides practical business recommendations. It’s a foundational example of combining database querying and spreadsheet modeling to drive sales strategy decisions.

---


