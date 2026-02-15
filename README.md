# Retail Customer Retention – Power BI Dashboard

## 📌 Project Overview

This project analyzes retail customer data to identify churn patterns, retention trends, loyalty impact, and Customer Lifetime Value (CLV) insights using Power BI.

The objective is to generate actionable business insights that support customer retention strategies and improve operational decision-making.

---

## 🛠 Tools & Technologies

- Microsoft Power BI  
- Power Query (Data Transformation)  
- DAX (Data Analysis Expressions)  
- Data Modeling  

---

## 🗂 Dataset Description

The dataset was provided in CSV format and imported into Power BI for transformation and analysis.

The dataset includes:

- Customer_Demographics.csv  
- Customer_Transactions.csv  
- Loyalty_Program.csv  
- Store_Locations.csv  
- Churn_Labelled_Customers.csv  

Data cleaning and transformation were performed using Power Query.  
Relationships were established between tables to enable cross-table analysis.

---

## 🔎 Key Analysis Performed

### 1️⃣ Data Preparation & Modeling
- Cleaned and transformed raw CSV data using Power Query  
- Built relationships between customer, transaction, store, and churn tables  
- Created calculated columns and DAX measures  

### 2️⃣ Retention & Churn Analysis
- Calculated Repeat Rate and Churn Rate  
- Analyzed churn by region, loyalty tier, income level, and sales channel  

### 3️⃣ Loyalty & Promotion Insights
- Measured % Transactions with Promotion  
- Compared average purchase behavior (with vs without promotion)  
- Evaluated loyalty tier purchase frequency  

### 4️⃣ Store & Channel Performance
- Analyzed average transaction amount by store type  
- Compared retention and churn by store opening year  
- Evaluated performance across sales channels  

### 5️⃣ Customer Segmentation & CLV Analysis
- Segmented customers into High and Low CLV groups  
- Analyzed churn reasons  
- Evaluated CLV trends by region and loyalty tier  
- Examined relationship between CLV and recency behavior  

---

## 📊 Key Business Insights

- Certain loyalty tiers demonstrate higher churn probability  
- Promotions increase transaction share but have limited impact on average purchase value  
- Superstores show comparatively higher churn rates  
- High CLV customers display stronger retention patterns  
- Recency behavior is strongly associated with churn risk  

---

## 📂 Project Structure

```
retail-customer-retention-dashboard/
│
├── Retail_Customer_Retention_Dashboard.pbix
├── data/
│   ├── Customer_Demographics.csv
│   ├── Customer_Transactions.csv
│   ├── Loyalty_Program.csv
│   ├── Store_Locations.csv
│   └── Churn_Labelled_Customers.csv
│
├── screenshots/
│   ├── executive_overview.png
│   ├── loyalty_promotion_insights.png
│   ├── store_channel_performance.png
│   └── customer_segmentation.png
│
└── README.md
```

---

## 📌 Conclusion

This project demonstrates practical business intelligence skills including data modeling, KPI development using DAX, customer segmentation, churn analysis, and interactive dashboard design using Power BI.

---
