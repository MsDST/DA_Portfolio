# DA_Portfolio
# Marketing Campaign Performance Analysis (SQL + Power BI)

Welcome to my marketing analytics portfolio project, where I analyze the performance of a digital marketing campaign dataset using **MySQL** for data wrangling and KPI calculation, and **Power BI** for interactive visualizations. This project demonstrates how data can drive smart marketing decisions and improve ROI.

---

## Project Objectives

- Measure overall marketing performance.
- Identify the most effective **campaign types** and **channels**.
- Assess **customer engagement behavior**.
- Conduct **A/B testing** on campaign strategies.
- Recommend ways to optimize **conversion rate** and **ad spend**.

---

## Tools & Technologies

- **Database**: MySQL Workbench
- **Visualization**: Power BI
- **Languages**: SQL, DAX
- **Dataset**: [Digital Marketing Campaign Dataset](#) *Shared by Rabie El Kharoua(https://www.kaggle.com/datasets/rabieelkharoua/predict-conversion-in-digital-marketing-dataset)*

---

## Step-by-Step Breakdown

### 1.  Data Wrangling (SQL)

- Checked for missing values and duplicates.
- Cleaned the dataset for analysis.
- Result: Dataset was clean with no missing values or duplicates
  
```SQL-Based 
-- Check for missing values
SELECT * FROM digital_marketing_campaign_dataset
WHERE Age IS NULL OR Gender IS NULL OR Income IS NULL OR AdSpend IS NULL;

-- Check for duplicates
SELECT CustomerID, COUNT(*) 
FROM digital_marketing_campaign_dataset 
GROUP BY CustomerID 
HAVING COUNT(*) > 1;
