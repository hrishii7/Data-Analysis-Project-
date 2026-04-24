# 📊 Zomato Data Analysis Dashboard (Power BI Project)

## 🔍 Overview

This project focuses on analyzing Zomato’s multi-domain dataset to extract meaningful insights related to **food trends, restaurant performance, user behavior, and order patterns**.

The dashboard is built using **Power BI**, with data sourced from Kaggle and transformed into a structured, analysis-ready format. The goal is to simulate a real-world food delivery analytics scenario and demonstrate end-to-end data handling—from raw ingestion to interactive visualization.

---

## 📁 Dataset Description

The project integrates multiple datasets to create a comprehensive analytical model:

* **Food** → Item-level details
* **Menu** → Menu offerings and pricing
* **Orders** → Transactional order data
* **Users** → Customer demographics
* **Restaurants** → Restaurant attributes (location, ratings, etc.)

---

## ⚙️ Data Processing & Transformation

### 🔧 Data Source

* Raw datasets imported from **Kaggle**

### 🧹 Data Cleaning (Power Query)

Performed extensive preprocessing using Power Query:

* Removed null and duplicate values
* Standardized column formats (dates, text, numeric)
* Cleaned inconsistent entries (e.g., order status variations)
* Split and transformed columns (e.g., time, categories)

---

## 🧮 Data Modeling

* Established relationships between tables:

  * Orders ↔ Users
  * Orders ↔ Restaurants
  * Menu ↔ Food
* Designed a **relational/star schema model** for optimized querying
* Ensured proper cardinality and filter direction

---

## 📊 DAX Calculations & Measures

Key business metrics were created using DAX:

* **Total Sales (Completed Orders Only)**
* **Total Orders (All Statuses)**
* **Average Order Value (AOV)**
* **Cancellation Rate**
* **Average Rating (Completed Orders Only)**
* **Average Delivery Time**
* **Profit / Estimated Profit (if cost available)**

These measures ensure accurate business logic and analytical consistency.

---

## 📈 Dashboard Features

### 🔝 KPI Section

* Total Sales 💰
* Total Orders 📦
* Average Order Value 💵
* Cancellation Rate 📉
* Average Rating ⭐

---

### 📊 Visual Insights

* Sales Trend Over Time (Line Chart)
* Order Status Distribution (Donut Chart)
* Top Restaurants by Sales (Bar Chart)
* Category-wise Item Performance
* City-wise Sales Analysis

---

### 🎛️ Interactivity

* Dynamic slicers:

  * Date
  * City
  * Restaurant
  * Category
* Drill-down capabilities for deeper insights

---

## 🧠 Key Insights

* Identified top-performing restaurants and categories
* Analyzed customer ordering behavior
* Measured operational efficiency using delivery time
* Evaluated cancellation trends and their impact

---

## 🚀 Tools & Technologies

* **Power BI** → Dashboard & Visualization
* **Power Query** → Data Cleaning & Transformation
* **DAX** → Calculations & KPIs
* **Kaggle** → Data Source

---

## ⚠️ Challenges & Solutions

* **Large dataset (lakhs of rows)** → Optimized using aggregation & modeling
* **Inconsistent data** → Cleaned using transformation logic
* **Metric accuracy** → Applied proper filters (e.g., Completed orders only)

---

## 🎯 Conclusion

This project demonstrates the complete workflow of a data analyst:

* Raw data handling
* Data transformation
* Data modeling
* KPI creation
* Dashboard storytelling

It highlights the ability to convert raw, unstructured data into actionable business insights using Power BI.

---

## 📌 Future Enhancements

* Integration with real-time data sources
* Advanced analytics (forecasting, clustering)
* Deployment with scheduled refresh

---
