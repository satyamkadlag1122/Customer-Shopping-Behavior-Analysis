# 🛍️ Customer Behaviour Analysis Dashboard

An end-to-end **Data Analytics and Power BI project** that analyzes customer purchasing behaviour, revenue, product performance, demographics, payment methods, shipping preferences, discounts, subscriptions, and location-wise performance.

---

## 🎯 Project Objective

To transform customer transaction data into an interactive Power BI dashboard and generate actionable insights related to **customer behaviour, revenue, products, and business performance**.

---

## 🛠️ Tech Stack

- **Python & Pandas** — Data cleaning and EDA
- **SQL Server** — Data storage and business analysis
- **Power Query** — Data transformation
- **Power BI** — Dashboard and visualization
- **DAX** — Measures and KPIs

---

Customer_Behaviour_Analysis/
├── README.md
├── Report-Customer Behaviour Analysis.pdf
├── cleaning.ipynb
├── customer_behaviour.pbix
├── customer_behaviour_sql.sql
└── customer_shopping_behavior.csv

## 🔄 Data Pipeline

1. Raw customer shopping data (`customer_shopping_behavior.csv`) prepared for analysis
2. Python and **Pandas** used for data cleaning and exploratory data analysis
3. Cleaned data analyzed using **SQL Server** with `customer_behaviour_sql.sql`
4. **Power Query** used for data transformation and preparation
5. **DAX** used to create calculated measures and KPIs
6. **Power BI** used to build interactive dashboards for customer behaviour, product performance, and location analysis

## 📊 Dashboard Pages

### 1. Customer Behaviour Analysis

[![Customer Behaviour Analysis](./images/Customer_Analysis.png)](./images/Customer_Analysis.png)

Provides an overall view of customer purchasing behaviour and spending patterns.

**Key KPIs:**
- Total Customers: **5,000**
- Unique Items: **30**
- Average Review: **3.62**
- Total Spend: **994,182.42**
- Average Spend: **198.84**

**Key Visuals:**
- Revenue by Gender
- Revenue by Category
- Shipping Type Analysis
- Revenue by Season
- Average Revenue by Location
- Revenue by Age Distribution
- Revenue by Payment Method

**Filters:**
- Category
- Gender
- Discount Applied
- Subscription Status

---

### 2. Product & Location Analysis

[![Product & Location Analysis](./images/Product & Location Analysis.png)](./images/Product & Location Analysis.png)

Focuses on identifying the best and worst-performing products and locations.

**Key Visuals:**
- Top 5 Items by Average Rating
- Top 5 Items by Revenue
- Top 5 Locations by Revenue
- Bottom 5 Items by Average Rating
- Low Revenue Products
- Bottom 5 Locations by Revenue

## 💡 Key Insights

- **5,000 customers** and **30 unique items** were analyzed, with total customer spending of **₹9.94 lakh**.
- **Electronics** generated the highest category revenue at approximately **₹0.38M**, followed by Accessories and Clothing.
- **Male customers** contributed the highest revenue at approximately **₹390.96K**, followed by Female and Other customers.
- **Headphones** generated the highest product revenue at approximately **₹138K**, followed by Phone, Bag, Laptop, and Watch.
- **New York** recorded the highest revenue among locations at approximately **₹187.12K**.
- **Jewelry** achieved the highest average rating of **3.8**, while Phone recorded the lowest rating among the analyzed products at **2.9**.
- **Debit Card** was the highest revenue-generating payment method at approximately **₹253.28K**.
- **Spring, Winter, and Summer** recorded the highest seasonal revenue at approximately **₹0.24M** each.
- **Standard and Express** shipping types recorded the highest customer counts.
- **Hoodie, Backpack, Sneakers, Gloves, and Jeans** were identified as low-revenue products.
- **Rhode Island, New Jersey, Florida, Hawaii, and Kansas** were among the lowest-revenue locations.
- The dashboard helps identify **customer preferences, product performance, revenue trends, and areas for business improvement**.
