
# 📊 Business Intelligence & Data Analytics Portfolio

**Tools & Technologies:** Power BI, Python, Pandas, NumPy, Plotly, Scikit-learn, Statsmodels, DAX, Jupyter Notebook

## 📌 Project Overview

This repository combines two data analytics projects demonstrating how business intelligence, exploratory data analysis, machine learning, and interactive visualization can support data-driven business decisions.

The projects focus on two business domains:

1. **Sales Analytics & Customer Insights** — Sales performance analysis in the metals manufacturing industry.
2. **Gold Procurement Strategy & Analytics** — Gold price analysis, customer segmentation, and procurement risk assessment in the jewellery retail industry.

Both projects transform business data into meaningful insights through data preparation, analytical modeling, visualization, and interactive Power BI dashboards.

---

# 🔹 Project 1: Sales Analytics & Customer Insights Dashboard

**Industry:** Metals Manufacturing  
**Tools:** Power BI, DAX, Data Cleaning, Data Visualization  
**Analysis Period:** April 2023 – March 2024

## 📌 Overview

Developed an interactive Power BI dashboard to analyze sales performance, customer behavior, transaction values, and monthly sales trends using 257 GST sales records from a metals manufacturing company.

The solution helps stakeholders monitor business performance and identify opportunities for improving customer relationships and sales planning.

## 📊 Dashboard Preview

### Sales Overview Dashboard

![Sales Overview Dashboard](01-Sales-Analytics-PowerBI/Screenshots/sales-overview.png)

### Customer Insights Dashboard

![Customer Insights Dashboard](01-Sales-Analytics-PowerBI/Screenshots/customer-insights.png)

## ✨ Key Features

- Monthly sales trend analysis using area charts.
- Monthly sales quantity analysis.
- Top-five customer analysis based on sales value.
- Maximum single-transaction sales monitoring.
- GST component analysis.
- KPI cards for sales count, customer count, average transaction value, and quantity sold.
- Interactive date and customer slicers.
- DAX calculations for financial metrics in lakhs and quantities in metric tonnes.

## 📈 Business Value

- Identifies high-value customers.
- Highlights monthly sales patterns and seasonal trends.
- Supports customer relationship management.
- Improves visibility into sales performance.
- Supports inventory planning and strategic sales decisions.

**Data Confidentiality:** The original company dataset is proprietary and is not included in this repository.

---

# 🔹 Project 2: Gold Procurement Strategy & Analytics Dashboard

**Industry:** Jewellery Retail  
**Tools:** Python, Pandas, Plotly, Scikit-learn, Statsmodels, Power BI  
**Analysis Period:** 2024–2025

## 📌 Overview

Developed a data-driven analytics solution to investigate jewellery sales patterns, gold price movements, customer segments, and procurement risks in a volatile gold pricing environment.

The project combines Python-based exploratory data analysis, statistical modeling, machine learning, and Power BI visualization to support informed procurement and business planning.

## 📊 Dashboard Preview

### Gold Procurement Analytics Dashboard

![Gold Procurement Dashboard](02-Gold-Procurement-Analytics/Screenshots/gold-procurement-dashboard.png)

## ✨ Key Features

### 1. Exploratory Data Analysis (EDA)

- Analyzed monthly sales trends and seasonal patterns.
- Examined relationships between sales, purchase behavior, and profit or loss.
- Investigated pricing patterns around auspicious occasions.
- Applied statistical summaries, correlation analysis, and trend analysis.

### 2. Gold Price Volatility Analysis

**GARCH Model**
- Modeled conditional volatility in gold prices.
- Examined changes in market risk over time.
- Used volatility estimates as one input for procurement risk assessment.

**Bollinger Bands**
- Analyzed price movements relative to rolling averages and standard deviations.
- Identified periods of relatively high or low prices compared with recent trends.

### 3. Anomaly Detection

**Local Outlier Factor (LOF)**

- Identified unusual transaction patterns.
- Flagged potentially abnormal sales, pricing, or volume observations for further investigation.

### 4. Customer Segmentation

**K-Means Clustering**

Segmented customers based on selected purchasing and profitability characteristics to support differentiated customer strategies.

The analysis explored segments such as:
- High-margin, low-volume customers.
- Low-margin, low-frequency customers.
- Bulk buyers.

### 5. Interactive Power BI Dashboard

- Monthly sales and purchase analysis.
- Net profit and loss visualization.
- Customer segment analysis.
- Transaction and pricing pattern monitoring.
- KPI-based business performance reporting.

## 📈 Business Value

- Supports data-driven procurement planning.
- Helps evaluate gold price volatility and purchasing risk.
- Identifies unusual transactions for further review.
- Enables customer segmentation and targeted engagement.
- Improves visibility into sales performance and profitability.

**Important:** Statistical indicators and model outputs are decision-support tools, not guarantees of future gold prices, profitable purchases, or financial returns.

---

# 🛠️ Technologies & Skills

| Category | Technologies |
|---|---|
| Business Intelligence | Power BI |
| Data Visualization | Power BI, Plotly |
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Statistical Analysis | Statsmodels |
| Machine Learning | Scikit-learn |
| Forecasting & Volatility | GARCH, Bollinger Bands |
| Anomaly Detection | Local Outlier Factor |
| Customer Segmentation | K-Means Clustering |
| Dashboard Calculations | DAX |
| Development Environment | Jupyter Notebook |

---

# 📂 Repository Structure

```text
Business-Intelligence-and-Data-Analytics/
│
├── README.md
├── .gitignore
│
├── 01-Sales-Analytics-PowerBI/
│   ├── Dashboard/
│   │   └── Audit.pbix
│   ├── Screenshots/
│   │   ├── sales-overview.png
│   │   └── customer-insights.png
│   └── Reports/
│       └── Sales-Report-Overview.pptx
│
└── 02-Gold-Procurement-Analytics/
    ├── Dashboard/
    │   └── ABC_Gold_Insights.pbix
    ├── Data/
    │   └── README.md
    ├── Notebooks/
    │   ├── EDA-and-Data-Profiling.ipynb
    │   └── ML-Models.ipynb
    ├── Screenshots/
    │   └── gold-procurement-dashboard.png
    └── Reports/
        └── Project-Report.pdf
```

*Note: This structure represents the recommended organization. Update filenames and paths to match the files actually committed to the repository. Include only datasets you are authorized to distribute.*

---

# 🎯 Key Learning Outcomes

- Developed interactive Power BI dashboards for business reporting.
- Applied data cleaning and preprocessing techniques to real-world datasets.
- Designed KPIs and calculated business metrics using DAX.
- Performed exploratory data analysis and statistical investigation.
- Applied volatility modeling and anomaly detection techniques.
- Used unsupervised machine learning for customer segmentation.
- Translated analytical findings into business-oriented recommendations.
- Communicated results through visual storytelling and dashboard design.

---

# 🚀 Conclusion

These projects demonstrate how business intelligence and data science can be applied across different industries to solve practical business problems.

The Sales Analytics Dashboard emphasizes sales performance, customer insights, and reporting, while the Gold Procurement Analytics Dashboard extends the analysis with statistical modeling, anomaly detection, customer segmentation, and procurement risk assessment.

Together, they showcase an end-to-end analytical skill set spanning data preparation, exploratory analysis, machine learning, visualization, and decision support.

**Objective:** Transform raw business data into actionable insights that support better decisions, improve business visibility, and enable data-driven strategy.

---

**Author:** Saravana Kumar  
**Focus Areas:** Data Science | Business Intelligence | Machine Learning | Data Visualization

**GitHub:** [Saravanakumarsk1210](https://github.com/Saravanakumarsk1210)
