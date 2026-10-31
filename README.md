
# 📊 Business Intelligence & Data Analytics Portfolio

**Author:** Saravana Kumar  
**Technologies:** Power BI, Python, Pandas, Plotly, Scikit-learn, Statsmodels, DAX, Jupyter Notebook

This repository contains two independent data analytics projects focused on solving real-world business problems through business intelligence, data visualization, statistical analysis, and machine learning.

## 📁 Projects Overview

| Project | Domain | Tools |
|---|---|---|
| Sales Dashboard & Insights | Metals Manufacturing | Power BI, DAX |
| ABC Gold Procurement Strategy Dashboard | Jewellery Retail | Python, Machine Learning, Power BI |

---

# 📈 Project 1: Sales Dashboard & Insights — Power BI

**Company:** Senthil Andavar Metal Company  
**Industry:** Metals Manufacturing  
**Analysis Period:** April 1, 2023 – March 31, 2024  
**Tool:** Microsoft Power BI

## 📝 Project Overview

This project focuses on analyzing and visualizing sales data using Power BI. The dataset contains 257 GST sales records and 28 unique customers from April 2023 to March 2024.

Through data cleaning, transformation, DAX calculations, and interactive visualizations, the dashboard provides insights into sales performance, customer behavior, transaction values, and monthly sales trends.

## 🔧 Data Preprocessing

![Data Preprocessing](https://drive.google.com/uc?export=view&id=1g0VZAMd1BiNr4XxmKlB29sHPJhPj79WH)

## 📊 Sales Dashboard

![Sales Dashboard](https://drive.google.com/uc?export=view&id=1lIFMqXEHvqS3B_j09_v4HjX4M7zuhD7j)

## 📈 Sales Overview Dashboard

![Sales Overview Dashboard](https://drive.google.com/uc?export=view&id=1RuYLJzFtR9WCEoTRuNa80dAgoC8A_Cmn)

## 👥 Customer Insights Dashboard

![Customer Insights Dashboard](https://drive.google.com/uc?export=view&id=1ZLpM4hY-5cTaTOncInzZEfm96s2qTdid)

## 🔧 Data Transformation

- Renamed columns for clarity.
- Converted text-based financial fields into numeric data types.
- Handled missing and null values.
- Formatted dates and standardized decimal precision.
- Created derived metrics for sales in lakhs and quantities in metric tonnes.
- Implemented DAX calculations for business KPIs.

## ✨ Dashboard Features

### Area Charts
- Monthly sales value in lakhs.
- Monthly quantity sold in metric tonnes.

### Bar Chart
- Top five customers by sales value.

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
- Filter by customer.

## 🚀 Key Business Outcomes

- **Sales Trend Analysis:** Identifies monthly sales patterns to support inventory planning.
- **Customer Insights:** Highlights high-value customers for relationship management.
- **Strategic Pricing and Promotions:** Helps identify peak and slower sales periods.
- **Performance Monitoring:** Provides a consolidated view of important sales KPIs.

**Data Confidentiality:** The original company dataset is proprietary and is not included in this public repository.

## 📂 Project Files

- `Audit.pbix` — Interactive Power BI dashboard.
- `Sales Report Overview.pptx` — Sales report presentation.
- `README.md` — Project documentation.

---

# 🪙 Project 2: ABC Gold — Procurement Strategy Dashboard

**Industry:** Jewellery Retail  
**Analysis Period:** 2024–2025  
**Tools:** Python, Pandas, Plotly, Scikit-learn, Statsmodels, Power BI

## 📌 Project Overview

This project analyzes jewellery sales patterns, gold price movements, customer segments, and procurement risks in a volatile gold pricing environment.

It combines exploratory data analysis, statistical modeling, machine learning, and Power BI visualization to support informed procurement planning and business decision-making.

## 📊 Gold Procurement Dashboard

![ABC Gold Procurement Strategy Dashboard](ABC-Gold-Procurement-Strategy-Dashboard/Screenshots/gold-procurement-dashboard.png)

*This image path assumes the screenshot is uploaded to the specified folder in the repository. Replace it with the actual path if your filename or folder differs.*

## 🧾 Dataset Sources

### Sales Data
- `Sales Data 1.csv` — Sales from April 2024 to September 2024.
- `Sales Data 2.csv` — Sales from October 2024 to March 2025.

### Market Data
- `Daily Rate Capture.csv` — Daily gold, silver, and platinum prices.
- `GoldBees Data.csv` — Indian gold ETF market data.

### Data Preparation

- Missing-value imputation.
- Unit standardization.
- Z-score-based outlier removal.
- Date and time parsing.
- One-hot encoding.
- Data type conversion and formatting.
- Merging and cleaning sales records.

## 📈 Exploratory Data Analysis

- Monthly sales trends and seasonal peaks.
- Relationships between profit/loss and purchasing behavior.
- Pricing patterns around Muhurtham (auspicious occasions).
- Descriptive statistics and group-wise aggregation.
- Seasonal decomposition and trend smoothing.
- Correlation heatmaps.
- Anomaly detection using Local Outlier Factor.

## 🤖 Statistical Modeling & Machine Learning

### 1. GARCH — Gold Price Volatility

- Models conditional volatility in gold prices.
- Evaluates changes in market risk over time.
- Supports risk-aware procurement analysis.

### 2. Bollinger Bands — Price Analysis

- Examines price movements relative to rolling averages and standard deviations.
- Helps identify relatively high and low price levels compared with recent trends.

### 3. Local Outlier Factor — Anomaly Detection

- Identifies unusual transaction patterns.
- Flags potentially abnormal pricing or quantities for further investigation.

### 4. K-Means — Customer Segmentation

The original analysis identified three customer segments:

- **Cluster 0:** High-margin, low-volume customers.
- **Cluster 1:** Low-margin, low-frequency buyers.
- **Cluster 2:** Bulk buyers.

These segments can support differentiated customer engagement and marketing strategies.

## 📊 Power BI Dashboard Features

- Monthly purchases and sales overview.
- Net profit/loss trends.
- Customer segment visualization.
- Transaction patterns and pricing insights.
- KPI-based business performance monitoring.
- Visual insights for procurement decisions.

## 🔍 Key Analytical Findings

| Focus Area | Contribution |
|---|---|
| Gold Price Volatility | GARCH evaluates changes in conditional volatility. |
| Price Analysis | Bollinger Bands contextualize prices against recent trends. |
| Sales Trends | Monthly analysis highlights seasonal patterns. |
| Anomaly Detection | LOF flags unusual transactions for further investigation. |
| Customer Segmentation | K-Means identifies distinct purchasing groups. |
| Procurement Strategy | Analytical indicators support informed purchasing decisions. |

## 🚀 Recommendations

- Evaluate procurement opportunities using gold price trends and volatility estimates.
- Investigate unusual transactions identified by LOF.
- Consider moving-average trends and calendar effects when planning inventory.
- Use customer segments to support targeted marketing.
- Review seasonal sales patterns when planning purchases and promotions.

*Statistical indicators and model outputs are decision-support tools. They do not guarantee future gold prices or procurement profitability.*

## 📂 Project Files

- `Cleaned csv/` — Cleaned and prepared datasets.
- `EDA and Data profiling/` — Exploratory analysis and data profiling.
- `ML models/` — Statistical modeling and machine learning.
- `Project report .pdf` — Project report.
- `README.md` — Project documentation.

---

# 🛠️ Technical Skills Demonstrated

| Category | Technologies and Skills |
|---|---|
| Business Intelligence | Power BI |
| Dashboard Calculations | DAX |
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Power BI, Plotly |
| Statistical Modeling | Statsmodels, GARCH |
| Machine Learning | Scikit-learn |
| Anomaly Detection | Local Outlier Factor |
| Customer Segmentation | K-Means Clustering |
| Price Analysis | Bollinger Bands |
| Development Environment | Jupyter Notebook |

---

# 🎯 Overall Portfolio Value

These projects demonstrate how analytics can address different business challenges across two industries.

The Sales Dashboard focuses on sales reporting, customer insights, and business performance monitoring in metals manufacturing.

The ABC Gold project applies statistical modeling, machine learning, customer segmentation, and price analysis to jewellery retail and procurement planning.

Together, they demonstrate practical skills in data preparation, exploratory analysis, interactive dashboard development, analytical modeling, and business insight communication.

---

# 👨‍💻 Author

**Saravana Kumar**

**Areas of Interest:** Data Science | Business Intelligence | Machine Learning | Data Analytics

**GitHub:** [Saravanakumarsk1210](https://github.com/Saravanakumarsk1210)

# 📊 Business Intelligence & Data Analytics Portfolio

**Author:** Saravana Kumar  
**Technologies:** Power BI, Python, Pandas, Plotly, Scikit-learn, Statsmodels, DAX, Jupyter Notebook

This repository contains two independent data analytics projects focused on solving real-world business problems through business intelligence, data visualization, statistical analysis, and machine learning.

## 📁 Projects Overview

| Project | Domain | Tools |
|---|---|---|
| Sales Dashboard & Insights | Metals Manufacturing | Power BI, DAX |
| ABC Gold Procurement Strategy Dashboard | Jewellery Retail | Python, Machine Learning, Power BI |

---

# 📈 Project 1: Sales Dashboard & Insights — Power BI

**Company:** Senthil Andavar Metal Company  
**Industry:** Metals Manufacturing  
**Analysis Period:** April 1, 2023 – March 31, 2024  
**Tool:** Microsoft Power BI

## 📝 Project Overview

This project focuses on analyzing and visualizing sales data using Power BI. The dataset contains 257 GST sales records and 28 unique customers from April 2023 to March 2024.

Through data cleaning, transformation, DAX calculations, and interactive visualizations, the dashboard provides insights into sales performance, customer behavior, transaction values, and monthly sales trends.

## 🔧 Data Preprocessing

![Data Preprocessing](https://drive.google.com/uc?export=view&id=1g0VZAMd1BiNr4XxmKlB29sHPJhPj79WH)

## 📊 Sales Dashboard

![Sales Dashboard](https://drive.google.com/uc?export=view&id=1lIFMqXEHvqS3B_j09_v4HjX4M7zuhD7j)

## 📈 Sales Overview Dashboard

![Sales Overview Dashboard](https://drive.google.com/uc?export=view&id=1RuYLJzFtR9WCEoTRuNa80dAgoC8A_Cmn)

## 👥 Customer Insights Dashboard

![Customer Insights Dashboard](https://drive.google.com/uc?export=view&id=1ZLpM4hY-5cTaTOncInzZEfm96s2qTdid)

## 🔧 Data Transformation

- Renamed columns for clarity.
- Converted text-based financial fields into numeric data types.
- Handled missing and null values.
- Formatted dates and standardized decimal precision.
- Created derived metrics for sales in lakhs and quantities in metric tonnes.
- Implemented DAX calculations for business KPIs.

## ✨ Dashboard Features

### Area Charts
- Monthly sales value in lakhs.
- Monthly quantity sold in metric tonnes.

### Bar Chart
- Top five customers by sales value.

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
- Filter by customer.

## 🚀 Key Business Outcomes

- **Sales Trend Analysis:** Identifies monthly sales patterns to support inventory planning.
- **Customer Insights:** Highlights high-value customers for relationship management.
- **Strategic Pricing and Promotions:** Helps identify peak and slower sales periods.
- **Performance Monitoring:** Provides a consolidated view of important sales KPIs.

**Data Confidentiality:** The original company dataset is proprietary and is not included in this public repository.

## 📂 Project Files

- `Audit.pbix` — Interactive Power BI dashboard.
- `Sales Report Overview.pptx` — Sales report presentation.
- `README.md` — Project documentation.

---

# 🪙 Project 2: ABC Gold — Procurement Strategy Dashboard

**Industry:** Jewellery Retail  
**Analysis Period:** 2024–2025  
**Tools:** Python, Pandas, Plotly, Scikit-learn, Statsmodels, Power BI

## 📌 Project Overview

This project analyzes jewellery sales patterns, gold price movements, customer segments, and procurement risks in a volatile gold pricing environment.

It combines exploratory data analysis, statistical modeling, machine learning, and Power BI visualization to support informed procurement planning and business decision-making.

## 📊 Gold Procurement Dashboard

![ABC Gold Procurement Strategy Dashboard](ABC-Gold-Procurement-Strategy-Dashboard/Screenshots/gold-procurement-dashboard.png)

*This image path assumes the screenshot is uploaded to the specified folder in the repository. Replace it with the actual path if your filename or folder differs.*

## 🧾 Dataset Sources

### Sales Data
- `Sales Data 1.csv` — Sales from April 2024 to September 2024.
- `Sales Data 2.csv` — Sales from October 2024 to March 2025.

### Market Data
- `Daily Rate Capture.csv` — Daily gold, silver, and platinum prices.
- `GoldBees Data.csv` — Indian gold ETF market data.

### Data Preparation

- Missing-value imputation.
- Unit standardization.
- Z-score-based outlier removal.
- Date and time parsing.
- One-hot encoding.
- Data type conversion and formatting.
- Merging and cleaning sales records.

## 📈 Exploratory Data Analysis

- Monthly sales trends and seasonal peaks.
- Relationships between profit/loss and purchasing behavior.
- Pricing patterns around Muhurtham (auspicious occasions).
- Descriptive statistics and group-wise aggregation.
- Seasonal decomposition and trend smoothing.
- Correlation heatmaps.
- Anomaly detection using Local Outlier Factor.

## 🤖 Statistical Modeling & Machine Learning

### 1. GARCH — Gold Price Volatility

- Models conditional volatility in gold prices.
- Evaluates changes in market risk over time.
- Supports risk-aware procurement analysis.

### 2. Bollinger Bands — Price Analysis

- Examines price movements relative to rolling averages and standard deviations.
- Helps identify relatively high and low price levels compared with recent trends.

### 3. Local Outlier Factor — Anomaly Detection

- Identifies unusual transaction patterns.
- Flags potentially abnormal pricing or quantities for further investigation.

### 4. K-Means — Customer Segmentation

The original analysis identified three customer segments:

- **Cluster 0:** High-margin, low-volume customers.
- **Cluster 1:** Low-margin, low-frequency buyers.
- **Cluster 2:** Bulk buyers.

These segments can support differentiated customer engagement and marketing strategies.

## 📊 Power BI Dashboard Features

- Monthly purchases and sales overview.
- Net profit/loss trends.
- Customer segment visualization.
- Transaction patterns and pricing insights.
- KPI-based business performance monitoring.
- Visual insights for procurement decisions.

## 🔍 Key Analytical Findings

| Focus Area | Contribution |
|---|---|
| Gold Price Volatility | GARCH evaluates changes in conditional volatility. |
| Price Analysis | Bollinger Bands contextualize prices against recent trends. |
| Sales Trends | Monthly analysis highlights seasonal patterns. |
| Anomaly Detection | LOF flags unusual transactions for further investigation. |
| Customer Segmentation | K-Means identifies distinct purchasing groups. |
| Procurement Strategy | Analytical indicators support informed purchasing decisions. |

## 🚀 Recommendations

- Evaluate procurement opportunities using gold price trends and volatility estimates.
- Investigate unusual transactions identified by LOF.
- Consider moving-average trends and calendar effects when planning inventory.
- Use customer segments to support targeted marketing.
- Review seasonal sales patterns when planning purchases and promotions.

*Statistical indicators and model outputs are decision-support tools. They do not guarantee future gold prices or procurement profitability.*

## 📂 Project Files

- `Cleaned csv/` — Cleaned and prepared datasets.
- `EDA and Data profiling/` — Exploratory analysis and data profiling.
- `ML models/` — Statistical modeling and machine learning.
- `Project report .pdf` — Project report.
- `README.md` — Project documentation.

---

# 🛠️ Technical Skills Demonstrated

| Category | Technologies and Skills |
|---|---|
| Business Intelligence | Power BI |
| Dashboard Calculations | DAX |
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Power BI, Plotly |
| Statistical Modeling | Statsmodels, GARCH |
| Machine Learning | Scikit-learn |
| Anomaly Detection | Local Outlier Factor |
| Customer Segmentation | K-Means Clustering |
| Price Analysis | Bollinger Bands |
| Development Environment | Jupyter Notebook |

---

# 🎯 Overall Portfolio Value

These projects demonstrate how analytics can address different business challenges across two industries.

The Sales Dashboard focuses on sales reporting, customer insights, and business performance monitoring in metals manufacturing.

The ABC Gold project applies statistical modeling, machine learning, customer segmentation, and price analysis to jewellery retail and procurement planning.

Together, they demonstrate practical skills in data preparation, exploratory analysis, interactive dashboard development, analytical modeling, and business insight communication.

---

# 👨‍💻 Author

**Saravana Kumar**

**Areas of Interest:** Data Science | Business Intelligence | Machine Learning | Data Analytics

**GitHub:** [Saravanakumarsk1210](https://github.com/Saravanakumarsk1210)
