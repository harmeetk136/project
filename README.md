# 📊 DATA ANALYST Internship Project 

---
## 📝 Project Overview

This project contains the implementation of the following tasks:

1. **Sales Decrease Analysis** in the "Others" category (2021 vs 2022)
2. **Customer First Order Time Analysis**

---

## ✅ Task 1: Sales Decrease in "Others" Category

### Description

Analyzed and compared the product-wise sales quantity of the "Others" category between 2021 and 2022. Identified the top 20 products with the greatest sales decrease.

### Key Steps

- Filtered data for 2021 and 2022
- Merged by `sku_name`
- Calculated:
  - Percentage difference
  - Sales trend classification: "DOWN", "UP", "FAIR"
- Visualized with a **horizontal bar chart**

## ✅ Task 2: Customer First Order Time Analysis

### Description

Calculated the average time taken by customers to place their first order after registering and visualized the distribution.

### Key Steps

- Created a field: `DATE_DIFF(order_date, registered_date, DAY)`
- Generated:
  - A **scorecard** for the average days
  - A **histogram** for the distribution

---

## 📊 Sample Outputs

- **Sales Decrease Chart** 
- **Customer Order Histogram** 

---
## 🚀 Dashboard
- **🔗 Live Dashboard:** [https://lookerstudio.google.com/reporting/bded3a7a-3b75-4be8-87b6-31fb3a717b48]
- **🔗 Live Dashboard:** [https://lookerstudio.google.com/reporting/40aecfcd-556e-4fce-b794-7cd12a4d4418]
- martsales_dashboard.png

---

## 📄 Internship Report

The report detailing objectives, tasks, challenges, and outcomes is available in `Internship Assignment Report.pdf`.

---
