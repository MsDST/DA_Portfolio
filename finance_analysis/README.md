#  Financial Data Analysis & Interactive Power BI Dashboard

This project delivers a comprehensive **financial performance analysis** using SQL for data preparation and **Power BI** for dynamic visualization. The goal was to uncover key trends, optimize discount strategies, and guide strategic decisions through clean, interactive reporting.

---

##  Tools Used
- **SQL** (MySQL Workbench) – for data extraction and cleaning  
- **Power BI** – for interactive dashboard design  
- **DAX** – for custom KPI calculations

---

## 1.  Data Cleaning & Preparation

###  SQL Preprocessing
To ensure accurate and clean data:
- Trimmed whitespaces in columns.
- Converted date formats from integer to `YYYY-MM-DD`.
- Replaced empty values in `Discounted_Band2` with `None`.
- Retained negative profits for accurate financial analysis.

---

##  Key Metrics & DAX Calculations

###  KPIs Analyzed

- **Total Revenue**  
  `= SUM(Financials[Sales])`

- **Total Expenses**  
  `= SUM(Financials[New_COGS]) + SUM(Financials[Discounts])`

- **Total Profit**  
  `= SUM(Financials[New_profit])`

- **Profit Margin %**  
  `= DIVIDE([Total Profit], [Total Revenue], 0)`

---

##  Power BI Dashboard Highlights

###  Dashboard Features

- Revenue & Profit by Product and Country  
- Profitability Breakdown by Segment  
- Expense & Discount Contribution Charts  
- Interactive Filters by **Date**, **Segment**, **Product**, and **Region**

---

##  Key Insights

- Top-performing products generate the majority of revenue  
- Discount-heavy items negatively impact profit margins  
- Manufacturing costs and regional performance drive profitability  
- Growth opportunities lie in consistently high-performing countries

---

##  Recommendations

- Optimize discounting strategies to boost margins
- Focus resources on consistently profitable products  
- Scale operations in regions with strong performance  

---

##  Summary

This project successfully:

-  Cleaned and structured complex financial data using SQL  
-  Defined and tracked key financial KPIs with DAX  
-  Built an interactive Power BI dashboard for revenue, expense, and profit analysis  
-  Delivered actionable insights to inform financial decision-making
