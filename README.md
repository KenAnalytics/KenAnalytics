Hi, I'm Dominic 
SQL PROJECT

<!--# 🏠 Real Estate Sales Analysis

## 📊 Overview
This project analyzes real estate sales data to uncover patterns in property prices, sales trends, and buyer preferences. Using **SQL** for querying and **Power BI** for visualization, this analysis helps real estate stakeholders make data-driven investment decisions.

---

## 🧰 Tools Used
- **SQL** – Data extraction, transformation, and aggregation
- **Power BI** – Interactive dashboards and data visualization
- **Excel/CSV** – For data cleaning and structure

---

## 🗂 Dataset
- File: `data/real_estate_sales.csv`
- Columns: `property_id`, `property_type`, `location`, `sale_date`, `sale_price`, `square_footage`, `bedrooms`, `bathrooms`, `agent_name`

---

## 📌 Key Questions
- What are the peak months for property sales?
- Which locations have the highest average sale prices?
- What is the distribution of property types sold?
- Is there a relationship between square footage and sale price?

---

## 🔍 Sample SQL Queries

### 1. Top 5 Expensive Locations
```sql
SELECT location, AVG(sale_price) AS avg_price
FROM real_estate_sales
GROUP BY location
ORDER BY avg_price DESC
LIMIT 5;

**KenAnalytics/KenAnalytics** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Sales Month thread
SELECT DATE_TRUNC('month', sale_date) AS month, COUNT(*) AS total_sales
FROM real_estate_sales
GROUP BY month
ORDER BY month;


-->
