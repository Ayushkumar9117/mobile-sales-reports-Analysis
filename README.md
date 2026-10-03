# 📊 Power BI Sales Dashboard

## 📌 Project Overview

This project is an interactive **Power BI Sales Dashboard** created to analyze
sales performance, revenue, products, customers, and overall business trends.

The dashboard helps transform raw sales data into meaningful visual insights
for better business understanding and decision-making.

---

## 🎯 Project Objectives

- Analyze overall sales performance
- Track total revenue and sales
- Identify top-performing products
- Analyze sales trends over time
- Understand customer and product performance
- Create interactive and easy-to-understand dashboards
- Generate useful business insights from sales data

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- Data Cleaning
- Data Transformation
- Data Visualization

---

## 📊 Dashboard Features

### 🔹 Sales Overview
- Total Sales
- Total Revenue
- Total Orders
- Key Performance Indicators (KPIs)

### 🔹 Product Analysis
- Top-selling products
- Product-wise sales performance
- Product contribution to total sales

### 🔹 Time Analysis
- Monthly sales trends
- Yearly performance
- Sales comparison over time

### 🔹 Interactive Filters
Users can explore the dashboard using filters and slicers based on available
data dimensions.

---

## 🔄 Data Preparation

The dataset was prepared before creating the dashboard.

Main steps included:

1. Importing the raw data into Power BI
2. Removing unnecessary records
3. Handling missing values
4. Cleaning and transforming columns
5. Changing appropriate data types
6. Creating calculated columns/measures
7. Building relationships where required
8. Creating the final dashboard

---

## 📐 DAX

DAX was used to create calculated measures and KPIs required for the dashboard.

Example:

```DAX
Total Sales = SUM('Sales Data'[Sales])
