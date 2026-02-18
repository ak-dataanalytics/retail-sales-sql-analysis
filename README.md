# 🛒 Retail Sales Analytics Using SQL

![SQL](https://img.shields.io/badge/SQL-Server-blue?style=flat&logo=microsoftsqlserver) ![Dataset](https://img.shields.io/badge/Dataset-50K%2B%20Transactions-green?style=flat) ![Period](https://img.shields.io/badge/Period-2015--2018-orange?style=flat)

> Comprehensive retail sales analysis using advanced SQL to evaluate revenue trends, customer retention, product performance, and growth dynamics across 50,000+ transactions spanning 4 years.

---

## 📌 Project Overview

This project digs into a real-world retail dataset to answer critical business questions around revenue, customers, and products. The goal was to simulate the kind of analysis a data analyst would deliver to business stakeholders — going beyond queries to surface actionable insights.

---

## ❓ Business Questions Solved

| # | Question |
|---|----------|
| 1 | What is the total revenue, total customers, and total products? |
| 2 | How does revenue trend month-over-month and year-over-year? |
| 3 | Which year and quarter generated the highest revenue? |
| 4 | What percentage of revenue comes from repeat vs. one-time customers? |
| 5 | How is revenue and customer base distributed across regions? |
| 6 | Which product categories and sub-categories drive the most revenue? |
| 7 | What percentage of total revenue comes from top-performing products? |
| 8 | How can customers be segmented using cumulative revenue (ABC analysis)? |

---

## 🔑 Key Findings

> ⚠️ *Replace the placeholders below with your actual query results*

- 💰 **Total Revenue:** $2,261,536 | **Total Customers:** 793 | **Total Products:** 1861  
- 🔁 **Repeat customers** generated **99.77%** of revenue 
- 🌍 **West region** contributed the highest revenue share 
- 📦 **Top 10 products** account for **10.82%** of total revenue *(concentration risk)*  
- 📈 **Highest MoM growth:** 2015-03 at **+1121%**  
- 🏆 **Best performing year:** 2018

---

## 🛠️ SQL Concepts Applied

| Category | Techniques Used |
|----------|----------------|
| **Aggregations** | SUM, COUNT, AVG, ROUND |
| **Filtering & Grouping** | GROUP BY, HAVING |
| **Window Functions** | LAG, DENSE_RANK, SUM OVER, ROWS BETWEEN |
| **Query Structuring** | CTEs, Subqueries, CROSS JOIN |
| **Growth Analysis** | MoM & YoY using LAG with time formatting |
| **Segmentation** | ABC Analysis using cumulative revenue distribution |

---

## 📁 Project Structure

```
retail-sales-sql-analysis/
│
├── 📄 business_insight_sql_analysis.sql   # All SQL queries with comments
├── 📊 Retail_sales_data.csv               # Raw dataset (50K+ records)
├── 📝 Insights.md                         # Key findings & business interpretation
└── 📖 README.md                           # Project documentation
```

---

## 🚀 How to Run

1. Import `Retail_sales_data.csv` into **SQL Server** as a table named `sales`
2. Run the queries in `business_insight_sql_analysis.sql` sequentially
3. Reference `Insights.md` for result interpretation

---

## 👤 Author

**AK Data Analytics**  
📎 [GitHub Profile](https://github.com/ak-dataanalytics)
