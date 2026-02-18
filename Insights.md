# 📊 Retail Sales Analysis – Key Insights

## 1️⃣ Executive Summary

This project analyzes 50,000+ retail transactions (2015–2018) to evaluate revenue performance, customer contribution, and product concentration risk. The objective was to generate business-ready insights using structured SQL analysis including growth metrics and segmentation logic.

---

## 2️⃣ Revenue Performance Overview

- Total Revenue: ₹ 22,61,536 
- Total Customers: 793 
- Total Products: 1861
- Top Revenue Year: 2018
- Highest Revenue Quarter: Q4 2018

### Insight:
Revenue demonstrates an overall growth trend with noticeable seasonal spikes across specific quarters, indicating demand cycles and potential promotional influence.

---

## 3️⃣ Month-over-Month (MoM) Growth

- Highest Monthly Growth: 1121% (March 2015)  
- Largest Monthly Decline: -75% (January 2017)  

### Insight:
Revenue fluctuations suggest seasonal demand sensitivity and potential macroeconomic or promotional impact.

---

## 5️⃣ Customer Segmentation (ABC Analysis)

Customers were segmented based on cumulative revenue contribution:

- A Category: Top revenue-generating customers  
- B Category: Moderate contribution customers  
- C Category: Low contribution customers  

### Insight:
A small percentage of customers contribute a disproportionately high share of total revenue, indicating revenue concentration risk and the importance of retention strategies.

---

## 6️⃣ Repeat vs One-Time Customers

- Revenue from Repeat Customers: 99.77%  
- Revenue from One-Time Customers: 0.23%  

### Insight:
Repeat customers contribute significantly to total revenue, emphasizing the value of customer retention and loyalty programs.

---

## 7️⃣ Regional Performance Analysis

- Top Performing Region: West
- Lowest Performing Region: South 

### Insight:
Regional disparities highlight opportunities for targeted marketing and expansion strategies in underperforming areas.

---

## 8️⃣ Product Revenue Concentration

- Revenue from Top 10 Products: 10.82% of total revenue  

### Insight:
High revenue concentration within limited products may increase operational risk if demand patterns shift.

---

## 9️⃣ Key Business Risks Identified

- Customer concentration dependency  
- Product concentration exposure  
- Seasonal revenue volatility  

---

## 🔟 Strategic Recommendations

- Strengthen engagement with high-value (A category) customers  
- Diversify product revenue contribution  
- Leverage seasonal peaks through targeted campaigns  
- Expand growth initiatives in low-performing regions  

---

## 🛠 Technical Approach

The analysis was performed using advanced SQL techniques including:

- Aggregations (SUM, COUNT, AVG)  
- GROUP BY and HAVING  
- Window Functions (LAG, DENSE_RANK)  
- CTEs (Common Table Expressions)  
- Cumulative revenue calculations  
- MoM and YoY growth analysis  
