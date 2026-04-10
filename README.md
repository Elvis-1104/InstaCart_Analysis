# 🛒 Instacart Customer & Product Analytics Dashboard

Instacart customer behavior analysis project using SQL, Python, and Power BI, focusing on customer segmentation, product reorder patterns, and category performance to generate data-driven business insights.

## 📌 Project Overview
This project focuses on analyzing customer purchasing behavior, product reorder patterns, and category-level performance using the Instacart dataset. The goal is to extract meaningful insights that can help in improving customer retention, optimizing product strategy, and understanding demand patterns.

The analysis follows a complete data pipeline — from raw data ingestion to dashboard creation — using SQL, Python, and Power BI.

---

## ❓ Problem Statement

The project aims to answer the following key business questions:

- Which customers are most likely to reorder?
- Which products drive repeat purchases?
- What purchasing patterns influence customer loyalty?
- How do order frequency and basket size impact engagement?

---

## 🎯 Objectives

1. **Customer Segmentation & Engagement**
   - Identify high-value customers based on order frequency
   - Calculate reorder ratio at customer level
   - Segment customers into high, medium, and low engagement groups

2. **Product Reorder & Loyalty Analysis**
   - Compute product-level reorder probability
   - Identify most frequently reordered products
   - Detect products with low repeat purchase rates

3. **Category & Department Performance**
   - Analyze department-wise and aisle-wise performance
   - Determine categories driving highest repeat purchases
   - Compare product diversity across departments

4. **Order Timing & Demand Patterns**
   - Analyze orders by day of week
   - Analyze orders by hour of day
   - Identify peak demand periods

---

## 🛠️ Tools & Technologies Used

- **Kaggle** – Dataset source  
- **Command Prompt** – Data loading into SQL database  
- **MySQL (SQL)** – Data storage and querying  
- **Python (Jupyter Notebook)**  
  - Data cleaning and preprocessing  
  - Exploratory Data Analysis (EDA)  
  - SQL integration using Python  
- **Power BI**  
  - Data visualization  
  - Report creation  
  - Dashboard development  

---

## 🔄 Project Workflow

1. **Data Collection**
   - Dataset downloaded from Kaggle

2. **Data Loading**
   - Data imported into MySQL database using command prompt

3. **Data Cleaning (Python)**
   - Handled missing values and inconsistencies
   - Cleaned columns (e.g., trimming, formatting categorical values)

4. **Data Analysis (SQL in Jupyter Notebook)**
   - Customer-level analysis
   - Product-level reorder analysis
   - Category and department insights

5. **Visualization (Power BI)**
   - Built multiple reports based on objectives
   - Created an interactive dashboard summarizing key insights

---

## 📊 Key Insights

### 👤 Customer Behavior
- Majority of customers fall into the medium engagement segment
- High-value customers place frequent orders with shorter gaps between purchases
- Reorder ratio shows a strong presence of moderately loyal customers

### 📦 Product Insights
- Most products have moderate reorder probability (0.5–0.7)
- Very few products show extreme loyalty or one-time purchase behavior
- High-order products tend to have more stable reorder patterns

### 🏬 Category Performance
- Certain departments (e.g., essentials) drive higher repeat purchases
- Product diversity varies across departments but does not guarantee loyalty
- Repeat purchases are concentrated in specific categories

### ⏰ Demand Patterns
- Orders peak during mid-day hours
- Early morning and late-night activity is minimal
- Demand varies slightly across days but remains relatively stable

---

## 📈 Dashboard Overview

The Power BI dashboard provides a consolidated view of:

- Key KPIs (Total Orders, Users, Products, Reorder Ratio)
- Customer segmentation insights
- Demand patterns (day & hour analysis)
- Top reordered products
- Category and department performance

The dashboard is designed for quick decision-making and business-level insights.

---

## 🚀 Conclusion

The analysis reveals that customer loyalty is driven by a combination of purchase frequency, product type, and category behavior. While most products show moderate repeatability, a small subset plays a crucial role in driving consistent engagement.

Businesses can leverage these insights to:
- Focus on high-performing product categories
- Improve retention strategies for low-engagement customers
- Optimize inventory based on demand patterns


---

## 📌 Author

**Elvis George**

---

