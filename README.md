# 📊 Customer Behavior Analysis

## 🔎 Project Overview

This project analyzes 3,900 customer transactions to identify spending patterns, customer segments, and revenue-driving factors.  

The analysis follows an end-to-end workflow from data cleaning to database querying and dashboard visualization.

---

## 🛠 Tools & Technologies

- Python (Pandas)
- PostgreSQL (pgAdmin 4)
- SQL
- Power BI

---

## 🧹 Data Preparation (Python - Jupyter Notebook)

- Handled missing values in review ratings
- Standardized column names using snake_case
- Created new features:
  - age_group
  - purchase_frequency_days
- Ensured data consistency before database integration

---

## 🗄 Database & SQL Analysis

The cleaned dataset was loaded into PostgreSQL.

Key analyses performed:

- Revenue by Gender
- Top 5 Products by Rating
- Shipping Type Purchase Comparison
- Subscriber vs Non-Subscriber Spending
- Revenue by Age Group
- Customer Segmentation (New, Returning, Loyal)

---

## 📊 Dashboard Preview

![Customer Dashboard](dashboard.png)

---

## 📈 Key Business Insights

- Clothing category generated the highest revenue
- 27% of customers are subscribers
- Express shipping slightly increases order value
- Loyal customers contribute majority of repeat purchases
- Certain products heavily depend on discounts

---

## 🎯 Business Recommendations

- Strengthen subscription benefits
- Optimize discount strategy
- Focus marketing on high-revenue age groups
- Highlight top-rated products for higher conversion
