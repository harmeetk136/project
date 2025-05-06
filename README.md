# project
Using MYSQL,Python and lookerstudio


# 📊 NULLCLASS Internship Project - Sales Analysis & Customer Behavior

Welcome to the internship task repository for the NULLCLASS program. This project includes in-depth data analysis tasks focusing on sales trends and customer order behavior.

---

## 📝 Project Overview

This project contains the implementation of the following tasks:

1. **Sales Decrease Analysis** in the "Others" category (2021 vs 2022)
2. **Customer First Order Time Analysis**

All work was completed using Python (pandas, matplotlib) and Tableau/Power BI as part of the NULLCLASS internship requirements.

---

## 📁 Folder Structure

```
.
├── Task-1_Sales_Decrease/
│   ├── sales_analysis_others.py
│   ├── sales_decrease_chart.png
│   ├── sales_difference_dataset.csv
│   └── README.md
├── Task-2_First_Order_Analysis/
│   ├── customer_order_delay_analysis.py
│   ├── histogram.png
│   ├── scorecard_screenshot.png
│   └── README.md
├── Internship_Report.pdf
├── dashboard.pbix  # or .twbx for Tableau
├── requirements.txt
└── README.md  # (this file)
```

---

## ✅ Task 1: Sales Decrease in "Others" Category

### Description

Analyzed and compared the product-wise sales quantity of the "Others" category between 2021 and 2022. Identified the top 20 products with the greatest sales decrease.

### Key Steps

- Filtered data for 2021 and 2022
- Merged by `sku_name`
- Calculated:
  - Absolute and percentage difference
  - Sales trend classification: "DOWN", "UP", "FAIR"
- Visualized with a **horizontal bar chart**

### Tools Used

- Python (pandas, matplotlib)
- Power BI (for additional dashboards)

---

## ✅ Task 2: Customer First Order Time Analysis

### Description

Calculated the average time taken by customers to place their first order after registering and visualized the distribution.

### Key Steps

- Created a field: `DATE_DIFF(order_date, registered_date, DAY)`
- Generated:
  - A **scorecard** for the average days
  - A **histogram** for the distribution

### Tools Used

- Tableau / Power BI
- SQL / Python (optional preprocessing)

---

## 📊 Sample Outputs

- **Sales Decrease Chart:** `sales_decrease_chart.png`
- **Customer Order Histogram:** `histogram.png`
- **Scorecard Screenshot:** `scorecard_screenshot.png`

---

## 🚀 Deployment

This project was integrated within the existing training project and hosted live (if applicable):

**🔗 Live Dashboard:** [Netlify/Vercel Link Here]

---

## 📄 Internship Report

The report detailing objectives, tasks, challenges, and outcomes is available in `Internship_Report.pdf`.

---

## 📬 Contact

For any queries related to this internship project, feel free to contact:

**Harmeet Kaur**  
Email: [your email]  
NULLCLASS Internship (2025)

