# 📊 Sales Data Dashboard (Power BI)

## 📊 Project Overview

This project presents an interactive business dashboard built using Power BI to analyse sales performance, profit trends, and regional insights. The dashboard enables users to explore key business metrics and identify patterns to support data-driven decision-making.

The project utilises pre-cleaned data and focuses on building meaningful visualisations and calculated measures using DAX to derive key performance indicators such as total sales, total profit, and profit margins.

The dashboard highlights sales trends over time, regional performance, and top-performing products, providing clear and actionable business insights.

## 🎯 Objectives

- Analyse total sales and profit performance  
- Compare sales across different regions  
- Identify top-performing products  
- Track sales trends over time  
- Provide interactive visual insights for business users  

## 📈 Dashboard Features

### 💰 Key Metrics
- Total Sales: 742K  
- Total Profit: 18.45K  

### 🌍 Regional Analysis
- Sales comparison across regions (West, East, Central, South)  
- West region shows highest sales performance  

### 🗺️ Geographic Insights
- Map visual showing sales and profit distribution across states  
- Helps identify high-performing locations  

### 📅 Sales Trend Analysis
- Year-wise sales growth visualisation  
- Shows consistent increase in sales over time  

### 🏆 Top Products
- Table showing top-performing products based on sales and profit  
- Helps identify high-revenue and low-profit items

- ## ⚡ DAX Measures

- Total Sales = SUM(Orders[Sales])
- Total Profit = SUM(Orders[Profit])
- 
-Sales by Year = CALCULATE(SUM(Orders[Sales]),YEAR(Orders[Order Date]))

### 🧩 Category Filter
- Interactive selection for:
  - Furniture  
  - Office Supplies  
  - Technology  

## 🛠️ Tools & Technologies

- Power BI  
- Data Visualisation  
- Data Analysis  

## 📌 Key Insights

- West region contributes the highest revenue  
- Sales show steady growth year over year  
- Some products generate high sales but low profit (cost issue)  
- Customer demand varies significantly by region and category  


## 📷 Dashboard Preview

<img width="1867" height="721" alt="image" src="https://github.com/user-attachments/assets/70c82c50-7734-4be5-b296-f2be8c86c771" />



## 🚀 Key Learning

This project strengthened my skills in:
- Business data analysis  
- Dashboard design and storytelling  
- Data visualisation best practices  
- Identifying actionable insights from data  
