# 📊 Sales Dashboard & Insights – Power BI Project

> **Author**: Saravana Kumar  
> **Region**: Madurai, Tamil Nadu  
> **Dataset Source**: Real-time sales and purchase data (2023–2024) from a metals manufacturing company  
> **Tool Used**: Power BI

**Please note that the dataset used to develop this dashboard has not been included  
here due to its proprietary nature and confidentiality agreements with the company.**

---

## 📝 Project Overview

This project focuses on analyzing and visualizing **real-time sales and purchase data** using Power BI. The data was sourced from Senthil Andavar Metal Company and spans the period from **April 1, 2023, to March 31, 2024**.

Through **data cleaning**, **transformation**, and **visualization**, the project uncovers key business metrics and customer insights to help enhance strategic sales decisions.

---

## 🧾 About the Dataset

- **Total Records**: 257  
- **Date Range**: 1st April 2023 – 31st March 2024  
- **Unique Customers**: 28  
- **Voucher Type**: GST Sales  
- **Metrics**:
  - Quantity (Kgs)
  - Gross Total (Dr)
  - GST Sales (Cr)
  - CGST, SGST, IGST, Round_Off

---
## Sales overview dashboard
![Sales Dashboard 1](https://drive.google.com/uc?export=view&id=1RuYLJzFtR9WCEoTRuNa80dAgoC8A_Cmn)

## Customer insights dashboard
![Sales Dashboard 2](https://drive.google.com/uc?export=view&id=1ZLpM4hY-5cTaTOncInzZEfm96s2qTdid)


## 🔧 Data Transformation

- **Column Formatting**: Renamed columns for clarity (e.g., "Quantity (Kgs)", "Rate (Kgs)").
- **Data Type Fixes**: Converted text-based financial fields into numeric types.
- **Cleaning**: Handled missing/null values, formatted dates, and ensured consistent rounding of decimal values.
- **Derived Columns**: Extracted metrics in Lakhs and Metric Tons (MT) using DAX calculations.

---

## 📈 Dashboard Visuals & Insights

### 🔹 Area Charts

- **Monthly Sales (in Lakhs)**  
  `Value in Lakhs = SUM(Sales[Gross Total (Dr)]) / 100000`

- **Quantity Sold per Month (in MT)**  
  `Value in kgs = SUM(Sales[Quantity (Kgs)]) / 1000`

### 🔹 Bar Chart

- **Top 5 Customers by Sales (in Lakhs)**  
  - Highlights high-value customers to assist in loyalty campaigns.

### 🔹 Gauge Chart

- **Maximum Single Transaction Sale (in Lakhs)**  
  - Tracks the highest-value order for performance benchmarking.

### 🔹 Pie Chart

- **GST Breakdown: GST Sales vs IGST vs SGST**  
  - Analyzes the tax distribution across transactions.

### 🔹 KPI Cards

- Total Number of Sales
- Total Number of Customers
- Average Sales per Transaction
- Average Quantity Sold
- Fastest Growing Month
- Peak Sales Day

### 🔹 Slicers

- Filter by Year & Month (e.g., 2023, 2024, April)
- Filter by Customer (e.g., Subham Traders)

---

## 🚀 Key Business Outcomes

- **Sales Trend Analysis**  
  Helps track seasonal growth and plan inventory accordingly.

- **Customer Segmentation**  
  Identifies top customers for relationship management.

- **Strategic Pricing & Promotions**  
  Informs pricing adjustments based on peak and slow periods.

- **Performance KPIs**  
  Offers a complete view of sales health and growth.

---

## 📂 Files Included

- `Audit.pbix` – Power BI file with dashboard
- `Cleaned_Sales_Data.xlsx` – Transformed dataset
- `README.md` – Project documentation

---



## 💡 Final Thoughts

This project demonstrates the power of **data visualization** in unlocking sales insights from raw financial data. By integrating **DAX calculations** and **interactive visuals**, the dashboard empowers stakeholders to make informed, data-driven decisions.

---


