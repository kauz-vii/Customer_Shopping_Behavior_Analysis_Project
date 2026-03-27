# 📊 Customer Intelligence & Revenue Optimization System

<p align="center">
  <img src="https://img.shields.io/badge/Tools-Python%20%7C%20SQL%20%7C%20PowerBI-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Level-Advanced-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Focus-Data%20Analytics-green?style=for-the-badge"/>
</p>

---

## 📌 Project Overview

This project simulates a **real-world, end-to-end data analytics workflow** to analyze customer shopping behavior and generate actionable business insights.

The objective is to help a retail business answer:

> **“How can customer data be leveraged to improve engagement, optimize marketing strategies, and increase revenue?”**

This project covers the **complete analytics lifecycle** — from raw data to business decision-making.

---

## 🎯 Objectives

* Perform data cleaning & transformation using Python
* Conduct business-driven analysis using SQL
* Build an interactive dashboard in Power BI
* Implement **RFM Analysis** for advanced customer segmentation
* Generate actionable business insights & recommendations

---

## 🗂️ Dataset

* 📦 Records: ~3,900 customers
* 📊 Features: 18 columns

### 🔍 Data Includes:

* Customer demographics (Age, Gender, Location)
* Purchase details (Item, Category, Amount)
* Behavioral metrics (Frequency, Reviews, Discounts)
* Subscription & shipping preferences

---

## ⚙️ End-to-End Workflow

---

### 🔹 1. Data Preparation & EDA (Python)

* Imported dataset using **pandas**
* Explored structure using `.info()` and `.describe()`
* Handled missing values using **category-wise median imputation**
* Standardized column names (snake_case)
* Performed feature engineering:

  * `age_group`
  * `purchase_frequency_days`
* Removed redundant columns (`promo_code_used`)
* Exported cleaned dataset

---

### 🔹 2. Advanced Analytics – RFM Segmentation (🔥 Key Highlight)

Implemented **RFM (Recency, Frequency, Monetary) Analysis**:

* **Recency:** Purchase frequency (days)
* **Frequency:** Number of previous purchases
* **Monetary:** Purchase amount

### 📊 Customer Segments:

* 💎 High Value Customers
* 🔁 Loyal Customers
* ⚠️ At Risk Customers
* 📉 Low Value Customers

👉 This step transforms the project from **basic analysis → real business intelligence**

---

### 🔹 3. SQL Analysis (Business Problem Solving)

Performed structured analysis using SQL to answer key business questions:

* Revenue distribution by gender
* High-spending customers using discounts
* Top-rated products
* Shipping type impact on spending
* Subscription vs non-subscription behavior
* Discount dependency by product
* Customer segmentation (New / Returning / Loyal)
* Top products within each category
* Repeat buyers vs subscription analysis
* Revenue contribution by age group

---

### 🔹 4. Power BI Dashboard (Data Visualization)

Built an **interactive dashboard** for stakeholders.

### 📊 Dashboard Features:

#### 🔹 KPI Cards:

* Total Customers
* Average Purchase Amount
* Average Review Rating

#### 🔹 Visualizations:

* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Sales by Age Group
* **Revenue by Customer Segment (RFM)** 🔥

#### 🔹 Filters (Slicers):

* Gender
* Category
* Subscription Status
* Shipping Type

---

## 📸 Dashboard Preview

![RFM Chart](./RFM-chart.jpg)

---

## 📌 Key Insights

* 📊 **Low-value segment contributes highest revenue volume** due to large customer base
* 💎 **High-value customers show strong revenue efficiency**
* 🚚 Customers using **express shipping spend more on average**
* 🎯 **Young adults are the highest revenue-generating segment**
* 💸 Discounts increase purchases but may reduce profit margins

---

## 💡 Business Recommendations

* 🎯 Target **high-value customers** with premium offers
* 🔁 Re-engage **at-risk customers** through personalized campaigns
* 💎 Build **loyalty programs** for repeat customers
* 🚚 Promote **faster shipping options** for higher spending
* 📢 Optimize **discount strategies** for better profitability

---

## 🛠️ Tools & Technologies

* 🐍 Python (Pandas, Data Analysis)
* 🗄️ SQL (PostgreSQL)
* 📊 Power BI (Data Visualization)
* 📓 Jupyter Notebook

---

## 📁 Project Structure

```
📦 Customer-Behavior-Analytics
│── data/
│── Customer_Shopping_Behavior_Analysis.ipynb
│── customer_rfm_analysis.csv
│── business problem queries.sql
│── customer_behavior_dashboard.pbix
│── report.pdf
│── README.md
```

---

## 🚀 How to Use

1. Clone the repository
2. Run the Python notebook:

   ```
   Customer_Shopping_Behavior_Analysis.ipynb
   ```
3. Load data into SQL database
4. Execute SQL queries
5. Open Power BI dashboard:

   ```
   customer_behavior_dashboard.pbix
   ```
6. Explore insights

---

## ⭐ Project Value

This project demonstrates:

* End-to-end data analytics workflow
* Strong Python + SQL integration
* Business-focused analytical thinking
* Advanced customer segmentation (RFM)
* Data storytelling using dashboards

---

## 👨‍💻 Author

**Kaushik Bhadra**

* Aspiring Data Analyst
* Skilled in SQL, Python & Data Visualization

---

## 📢 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/kaushikbhadra07" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Kaushik%20Bhadra-blue?style=for-the-badge&logo=linkedin" />
  </a>
</p>
