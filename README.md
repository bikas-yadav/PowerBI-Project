# E-Commerce Sales Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Status](https://img.shields.io/badge/Project-Portfolio-blue)
![Domain](https://img.shields.io/badge/Domain-Data%20Analytics-success)

## Overview
The **E-Commerce Sales Dashboard** is an interactive Business Intelligence solution built using **Power BI** to analyze and visualize e-commerce sales data. This project converts raw transactional data into meaningful insights to support strategic and operational decision-making.

It showcases my ability to perform end-to-end data analytics including data cleaning, modeling, DAX calculations, and professional dashboard design.

---

## Live Dashboard Preview
(Insert dashboard screenshot here)

> Tip: Add a high-quality screenshot or GIF of your dashboard to make your GitHub portfolio more impactful.

---

## Objectives
- Monitor overall business performance  
- Track key KPIs for sales and profitability  
- Identify trends in customer purchasing behavior  
- Evaluate product and regional performance  
- Support management with data-driven insights  

---

## Key Performance Indicators (KPIs)
- Total Sales: 114K  
- Total Profit: 11K  
- Total Quantity Sold: 1245  
- Average Order Value (AOV): 31K  

---

## Dashboard Features
- Interactive filters by Quarter (Q1 – Q4)  
- Dynamic KPI cards  
- Drill-down and cross-filtering capabilities  
- Category & Sub-category level analysis  
- State-wise and customer-wise performance  
- Trend analysis for monthly profit  
- Payment mode distribution insights  

---

## Visual Components
- Sales by State (Bar Chart)  
- Sales by Customer (Column Chart)  
- Quantity by Category (Donut Chart)  
- Profit by Month (Bar Chart)  
- Profit by Sub-Category (Horizontal Bar Chart)  
- Quantity by Payment Mode (Donut Chart)  

---

## Tools & Technologies
- Power BI  
- Power Query  
- DAX (Data Analysis Expressions)  
- Microsoft Excel  
- Data Modeling Techniques  

---

## Dataset Information
The dataset consists of e-commerce transactional records with the following attributes:
- Order ID  
- Customer Name  
- State  
- Product Category  
- Sub-Category  
- Quantity  
- Sales Amount  
- Profit  
- Payment Mode  
- Order Date  

Data preprocessing was performed using Power Query, including:
- Handling missing values  
- Removing duplicates  
- Data type formatting  
- Column standardization  

---

## DAX Measures Examples
```DAX
Total Sales = SUM(Sales[Amount])

Total Profit = SUM(Sales[Profit])

Average Order Value = 
DIVIDE([Total Sales], DISTINCTCOUNT(Sales[Order ID]))
