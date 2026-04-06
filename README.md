# 📊 E-commerce Data Analysis using SQL

## 🎯 Project Overview

This is an end-to-end **Data Analysis Project** using **SQL Server (SSMS)** and **Power BI**.
The project focuses on analyzing retail business data to generate actionable insights on **sales, profit, customers, and product performance**.

---

## 🛠️ Tools & Technologies

* **SQL Server (SSMS)** – Database design, data modeling, and analysis
* **Power BI** – Data visualization and dashboard creation
* **DAX** – Calculated measures and KPIs
* **CSV Dataset** – Superstore sales dataset

---

## 🗄️ Database Design

A normalized database schema was created to improve performance and scalability.

### Tables:

* **Customers**
* **Products**
* **Locations**
* **Orders (Fact Table)**

✔ Implemented **Primary Keys & Foreign Keys**
✔ Added **Indexes for performance optimization** 

---

## 📥 Data Import Process

* Imported raw dataset into **staging table**
* Cleaned and transformed data
* Loaded into dimension and fact tables

### Key Steps:

1. Bulk insert CSV into staging table
2. Populate dimension tables (Customers, Products, Locations)
3. Load cleaned data into Orders table
4. Handle duplicates using ROW_NUMBER()

✔ Ensured data validation and consistency 

---

## 📊 SQL Analysis (Business KPIs)

Performed advanced SQL analysis including:

* 📈 Total Sales, Profit, Profit Margin
* 🛍️ Sales & Profit by Category
* 🏆 Top 10 Best Selling Products
* 📉 Loss-Making Products
* 🌍 Regional Performance
* 👥 Customer Segment Analysis
* 📅 Monthly & Yearly Trends
* 🎯 Discount Impact Analysis
* 🔁 Customer Retention Analysis
* 🏙️ City & State Performance

✔ Created reusable **Power BI View**:

* `vw_powerbi_sales` for dashboard integration 

---

## 📊 Power BI Dashboard

The dashboard is divided into **3 main pages**:

---

### 📍 Page 1: Executive Overview

* Total Sales, Profit, Quantity, Profit Margin
* Sales Trend Over Time
* Sales by Category & Region
* Profit/Loss by Subcategory
* Sales vs Profit Analysis

👉 Provides quick business performance insights

---

### 👥 Page 2: Customer & Segment Analysis

* Total Customers & Avg Metrics
* Sales & Profit by Segment
* Top 10 Customers
* Customer Profitability Analysis
* Repeat vs One-time Customers

👉 Helps understand customer behavior

---

### 📦 Page 3: Product & Profit Analysis

* Top & Loss-making Products
* Sales by Subcategory (Treemap)
* Quantity Sold Analysis
* Discount Impact on Profit
* Detailed Product Table

👉 Identifies profitable and risky products

---

## 📌 Key Insights

* Some subcategories generate high sales but low profit
* High discounts negatively impact profitability
* A small group of customers contributes major revenue
* Certain products consistently generate losses
* Sales show a steady growth trend over time

---

## 🚀 Features

* Interactive filters (Region, Segment, Category, Date)
* Dynamic KPIs using DAX
* Clean and professional UI
* Business-focused insights

---

## 📷 Dashboard Preview

<img width="1292" height="730" alt="image" src="https://github.com/user-attachments/assets/16de6579-45ed-4b1c-893b-4efea084ca42" />

<img width="1288" height="733" alt="image" src="https://github.com/user-attachments/assets/5a301e73-33d4-45ca-88c0-1a78870d7d55" />

---

## 🎯 Conclusion

This project demonstrates:

* Strong SQL skills (data modeling + analysis)
* Power BI dashboard development
* Business understanding and insight generation

---

## 💼 Author

**Srijan Yadav**
Aspiring Data Analyst | Python & Power BI Enthusiast

---
