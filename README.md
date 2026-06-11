# E-commerce Data Warehouse Project

## 📌 Project Overview

This project consists in building a mini data warehouse from an e-commerce dataset (Olist).
The goal is to structure raw data into analytical tables to support business analysis.

---

## 🎯 Business Objectives

- Analyze sales performance
- Identify best-selling product categories
- Measure delivery performance
- Build a structured data model (facts & dimensions)

---

## 📊 Dataset

The dataset used comes from the Olist Brazilian e-commerce platform and includes:

- Orders
- Products
- Customers
- Sellers
- Payments
- Reviews

---

## 🏗️ Data Warehouse Architecture

The project is based on a star schema:

- Fact table: sales data (fact_sales)
- Dimension tables:
  - dim_products
  - dim_orders
  - dim_sellers
  - dim_customers

---

## 📈 Analyses Performed

- Total revenue calculation
- Revenue by product category
- Delivery time analysis
- Late delivery rate
- Order status distribution

---

## 🔍 Key Findings

- Total revenue: ~13.5M
- Average delivery time: ~12 days
- Late deliveries: ~6.6%
- Some product categories strongly dominate sales

---

## 🛠️ Technologies Used

- Python
- Pandas
- Jupyter Notebook

---

## 💡 Skills Demonstrated

- Data cleaning & preprocessing
- Data modeling (star schema)
- KPI creation
- Business-oriented analysis
- Data storytelling

---

## 🚀 Future Improvements

- Deeper customer analysis (segmentation)
- Dashboard creation (Power BI / Tableau)
- Predictive modeling for delivery delays
