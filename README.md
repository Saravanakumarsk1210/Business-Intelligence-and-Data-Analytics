
# 📊 Business Intelligence & Data Analytics Portfolio

**Author:** Saravana Kumar  
**Focus Areas:** Business Intelligence | Data Analytics | Machine Learning | Data Visualization

**Technologies:** Power BI, Python, Pandas, Plotly, Scikit-learn, Statsmodels, DAX, Jupyter Notebook

## 📌 Portfolio Overview

This repository brings together two independent business analytics projects developed to solve different real-world business problems.

- **Project 1 — Sales Dashboard & Insights:** An interactive Power BI solution for monitoring sales performance, analyzing customer behavior, and understanding sales trends in the metals manufacturing industry.
- **Project 2 — ABC Gold Procurement Strategy Dashboard:** A data science and business intelligence solution combining exploratory data analysis, statistical modeling, machine learning, and Power BI to analyze jewellery sales, gold price movements, customer segments, and procurement risks.

Although both projects use data analytics and visualization, they address different business objectives and are maintained as separate projects within this repository.

---

# 📈 Project 1: Sales Dashboard & Insights — Power BI

**Industry:** Metals Manufacturing  
**Company:** Senthil Andavar Metal Company  
**Analysis Period:** April 1, 2023 – March 31, 2024  
**Primary Tool:** Microsoft Power BI

## 📝 Project Overview

This project focuses on analyzing and visualizing sales data using Power BI. The dataset contains 257 GST sales records and covers sales transactions from April 2023 to March 2024.

Through data cleaning, transformation, DAX calculations, and interactive visualizations, the dashboard provides insights into sales performance, customer behavior, transaction values, and monthly sales trends.

The objective is to help stakeholders monitor business performance and make informed sales and inventory planning decisions.

## 🧾 Dataset Information

- **Total Records:** 257
- **Unique Customers:** 28
- **Date Range:** April 1, 2023 – March 31, 2024
- **Voucher Type:** GST Sales

### Key Data Fields

- Quantity (Kgs)
- Gross Total (Dr)
- GST Sales (Cr)
- CGST
- SGST
- IGST
- Round_Off

The original company dataset is proprietary and has not been included in this public repository.

## 🔧 Data Transformation

- Renamed columns for improved readability.
- Converted text-based financial fields into numeric data types.
- Handled missing and null values.
- Formatted dates and standardized decimal precision.
- Created derived metrics for sales in lakhs and quantities in metric tonnes.
- Implemented DAX calculations for business KPIs.

## 📊 Dashboard Visualizations

### 1. Sales Overview Dashboard

Analyzes overall sales performance and monthly trends.

### 2. Customer Insights Dashboard

Provides a customer-level view of sales performance and purchasing patterns.

## ✨ Key Dashboard Features

### Area Charts
- Monthly sales value in lakhs.
- Monthly quantity sold in metric tonnes.

### Bar Chart
- Top five customers ranked by sales value.

### Gauge Chart
- Maximum single-transaction sale value.

### Pie Chart
- GST component breakdown.

### KPI Cards
- Total number of sales.
- Total number of customers.
- Average sales per transaction.
- Average quantity sold.
- Fastest-growing month.
- Peak sales day.

### Interactive Slicers
- Filter by year and month.
- Filter by individual customer.

## 🚀 Key Business Outcomes

**Sales Trend Analysis:** Identifies monthly sales patterns to support inventory planning.

**Customer Insights:** Highlights high-value customers for relationship management and customer-focused strategies.

**Strategic Pricing and Promotions:** Helps identify peak and slower sales periods.

**Performance Monitoring:** Provides a consolidated view of important sales KPIs.

## 📂 Project Files

- `Audit.pbix` — Interactive Power BI dashboard.
- `Sales Report Overview.pptx` — Sales dashboard presentation.
- `README.md` — Project documentation.

---

# 🪙 Project 2: ABC Gold — Procurement Strategy Dashboard

**Industry:** Jewellery Retail  
**Analysis Period:** 2024–2025  
**Tools:** Python, Pandas, Plotly, Scikit-learn, Statsmodels, Power BI

## 📌 Project Overview

ABC Gold is a premium jewellery retail business operating in a market influenced by fluctuating gold prices.

The objective of this project is to analyze sales and pricing patterns, investigate gold price volatility, identify unusual transactions, segment customers, and support data-driven procurement strategies.

The solution combines exploratory data analysis, statistical modeling, machine learning, and interactive Power BI dashboards to support purchasing decisions and profitability analysis.

## 📊 Dataset Sources

### Raw Datasets
- `Sales Data 1.csv` — Sales records from April 2024 to September 2024.
- `Sales Data 2.csv` — Sales records from October 2024 to March 2025.
- `Daily Rate Capture.csv` — Daily metal prices, including gold, silver, and platinum.
- `GoldBees Data.csv` — GoldBees ETF market data.

### Data Preparation

The datasets were cleaned and prepared through:

- Missing-value imputation.
- Unit standardization.
- Z-score-based outlier removal.
- Date and time parsing.
- One-hot encoding.
- Data type conversion and formatting.
- Merging and cleaning sales records.

## 📈 Exploratory Data Analysis (EDA)

Conducted using the `Trend_and_Pattern_Analysis` notebook.

### Areas Investigated

- Monthly sales trends and seasonal peaks.
- Relationships between profit/loss and purchasing behavior.
- Pricing patterns around Muhurtham (auspicious occasions).
- Unusual transactions and pricing observations.
- Correlations between relevant business variables.

### Analytical Techniques

- Descriptive statistics and group-wise aggregation.
- K-Means clustering using the Elbow Method.
- Seasonal decomposition and trend smoothing.
- Correlation heatmaps.
- Local Outlier Factor for anomaly detection.

## 🤖 Predictive Modeling & Risk Analysis

### 1. Gold Price Volatility — GARCH

Applied a Generalized Autoregressive Conditional Heteroskedasticity (GARCH) model to examine conditional volatility in gold prices.

**Objective:**
- Understand changes in gold price volatility.
- Assess market risk during different periods.
- Support risk-aware procurement planning.

The original analysis identified a period of relatively low modeled volatility as a potentially favorable condition for evaluating bulk purchases.

### 2. Price Analysis — Bollinger Bands

Used Bollinger Bands to examine gold price movements relative to a rolling average and its standard deviation.

**Objective:**
- Identify relatively high and low price levels.
- Examine price movements and potential procurement opportunities.
- Provide additional context for purchasing decisions.

Bollinger Bands are analytical indicators, not guaranteed buy or sell signals.

### 3. Anomaly Detection — Local Outlier Factor (LOF)

Applied Local Outlier Factor to identify transactions that differ from typical patterns.

**Applications:**
- Flag unusual sales values.
- Investigate abnormal transaction quantities.
- Identify potentially irregular pricing patterns for further review.

### 4. Customer Segmentation — K-Means Clustering

Applied K-Means clustering to group customers according to selected purchasing and profitability characteristics.

The original analysis identified three customer segments:

- **Cluster 0:** High-margin, low-volume customers.
- **Cluster 1:** Low-margin, low-frequency buyers.
- **Cluster 2:** Bulk buyers.

These segments can help inform customer engagement, marketing, and sales strategies.

## 📊 Power BI Dashboard

Developed the `ABC_Gold_Insights.pbix` dashboard to visualize business performance and analytical findings.

### Dashboard Highlights

- Monthly purchases and sales overview.
- Net profit/loss trends.
- Customer segments based on clustering results.
- Transaction patterns and pricing insights.
- KPIs to support procurement decisions.

## 🔍 Key Insights

| Focus Area | Analytical Contribution |
|---|---|
| Gold Price Volatility | GARCH analysis evaluates changes in conditional market volatility. |
| Price Patterns | Bollinger Bands help contextualize prices against recent trends. |
| Sales Trends | Monthly analysis highlights seasonal patterns and changes in sales activity. |
| Anomaly Detection | LOF flags unusual transactions for further investigation. |
| Customer Segmentation | K-Means identifies customer groups with different purchasing characteristics. |
| Procurement Strategy | Multiple analytical signals support informed purchasing and inventory decisions. |

## 🚀 Recommendations

- Evaluate procurement opportunities using gold price trends and volatility estimates.
- Investigate unusual transactions identified by LOF.
- Consider moving-average trends and relevant calendar effects when planning inventory.
- Use customer segments to support targeted marketing and customer engagement.
- Review seasonal sales patterns when planning purchasing and promotional activities.

These recommendations are analytical decision-support suggestions and do not guarantee future gold prices or profitability.

## 📂 Project Files

- `Cleaned csv/` — Cleaned and prepared datasets.
- `EDA and Data profiling/` — Exploratory analysis and data profiling.
- `ML models/` — Statistical modeling and machine learning.
- `Project report .pdf` — Project report.
- `README.md` — Project documentation.

---

# 🛠️ Technical Skills Demonstrated

| Skill Area | Application |
|---|---|
| Business Intelligence | Interactive Power BI dashboards |
| Data Preparation | Data cleaning, transformation, and validation |
| Data Visualization | Power BI and Plotly |
| Business Metrics | DAX calculations and KPI development |
| Exploratory Analysis | Statistical summaries, trends, and correlations |
| Statistical Modeling | GARCH-based volatility analysis |
| Machine Learning | K-Means clustering |
| Anomaly Detection | Local Outlier Factor |
| Price Analysis | Bollinger Bands |
| Business Analytics | Sales analysis, customer insights, and procurement planning |

---

# 🎯 Overall Portfolio Value

Together, these two independent projects demonstrate the application of data analytics to different business challenges.

The first project focuses on **sales reporting, customer insights, and interactive business intelligence** in metals manufacturing.

The second project extends into **statistical modeling, machine learning, customer segmentation, and procurement risk analysis** in jewellery retail.

They showcase practical skills in data preparation, exploratory analysis, dashboard development, analytical modeling, and communicating business insights.

---

## 👨‍💻 Author

**Saravana Kumar**

**Areas of Interest:** Data Science | Business Intelligence | Machine Learning | Data Analytics

**GitHub:** [Saravanakumarsk1210](https://github.com/Saravanakumarsk1210)
