
# 📊 Business Intelligence & Data Analytics Portfolio

A collection of two independent business analytics projects demonstrating data cleaning, exploratory data analysis, machine learning, financial analysis, and interactive Power BI dashboards.

## 👋 About This Portfolio

This repository brings together two projects focused on transforming business data into actionable insights:

1. **ABC Gold – Procurement Strategy Dashboard (2024–2025):** Combines Python, statistical modeling, machine learning, and Power BI to explore jewellery sales, metal-price trends, customer segments, and procurement decisions.
2. **Sales Dashboard & Insights – Power BI Project (2023–2024):** Uses Power BI and DAX to analyze sales performance, customer activity, transaction values, and tax-related metrics for a metals manufacturing company.

Each project has its own objectives, analytical workflow, and deliverables. They are documented separately below.

---

# 🪙 Project 1: ABC Gold – Procurement Strategy Dashboard (2024–2025)

> **Tools:** Python, Pandas, Plotly, Scikit-learn, Statsmodels, Power BI  
> **Data sources:** Internal sales data, daily metal prices, and GoldBees ETF data  
> **Focus:** Sales analysis, price volatility, customer segmentation, and procurement decision support

## 📌 Project Overview

ABC Gold is a jewellery-retail analytics case study focused on understanding sales patterns and operating in a market affected by fluctuating gold prices.

The project aims to:

- Analyze sales, profitability, and pricing patterns.
- Examine gold-price volatility to support procurement planning.
- Identify unusual transactions and customer segments.
- Explore seasonal trends and purchasing behavior.
- Present business insights through an interactive Power BI dashboard.

The solution combines exploratory data analysis, statistical modeling, machine learning, and visualization to support data-informed decisions.

## 📂 Datasets

### Raw datasets

| Dataset | Description |
|---|---|
| `Sales Data 1.csv` | Sales records from April to September 2024 |
| `Sales Data 2.csv` | Sales records from October 2024 to March 2025 |
| `Daily Rate Capture.csv` | Daily gold, silver, and platinum prices |
| `GoldBees Data.csv` | GoldBees ETF market data |

### Cleaned datasets

| Dataset | Description |
|---|---|
| `Sales Data.csv` | Merged and cleaned sales records |
| `Daily Rate Capture.csv` | Cleaned daily metal-price data |
| `GoldBees Data.csv` | Cleaned ETF dataset |

### Data preprocessing

The preprocessing workflow includes:

- Missing-value imputation.
- Unit standardization.
- Z-score-based outlier detection and removal.
- Date and time parsing.
- One-hot encoding of categorical variables.
- Data-type conversion and formatting.

### Preprocessing visualization

![ABC Gold data preprocessing](https://drive.google.com/uc?export=view&id=1g0VZAMd1BiNr4XxmKlB29sHPJhPj79WH)

## 📈 Exploratory Data Analysis

The notebook `Trend_and_Pattern_Analysis.ipynb` explores sales trends, customer behavior, and market-related patterns.

### Areas investigated

- Monthly sales trends and seasonal peaks.
- Relationships between profit/loss and purchasing behavior.
- The association between Muhurtham (auspicious days) and sales or pricing patterns.
- Unusual observations using Local Outlier Factor (LOF).
- Customer purchasing patterns and transaction characteristics.

### Techniques

- Descriptive statistics and group-wise aggregation.
- K-Means clustering with the Elbow Method.
- Seasonal decomposition and trend smoothing.
- Correlation analysis and heatmaps.

## 🤖 Predictive Modeling and Risk Analysis

The notebook `ML models.ipynb` contains the project's modeling and analytical experiments.

### 1. GARCH volatility modeling

The Generalized Autoregressive Conditional Heteroskedasticity (GARCH) model is used to examine conditional volatility in the analyzed price series.

**Purpose:** Understand changes in price volatility and provide additional context for procurement planning.

The original analysis reported periods of relatively low volatility. This should be interpreted in the context of the selected dataset and analysis period—not as a guarantee that future prices will remain stable.

### 2. Bollinger Bands

Bollinger Bands are used to examine price movements relative to a moving average and a measure of recent variability.

**Analytical use:** Investigate whether prices are near the upper or lower bands and compare those observations with other market indicators.

Band positions alone do not establish that a price is overvalued or undervalued and should not be treated as standalone buy/sell instructions.

### 3. Anomaly detection with LOF

Local Outlier Factor identifies observations that differ from their local neighborhood.

Potential applications include investigating unusual transaction values, quantities, or pricing patterns. A detected anomaly requires further review; it does not, by itself, prove fraud or price manipulation.

### 4. Customer segmentation with K-Means

The reported cluster profiles are:

| Cluster | Observed profile |
|---|---|
| Cluster 0 | High-margin, low-volume customers |
| Cluster 1 | Low-margin, low-frequency buyers |
| Cluster 2 | Bulk buyers |

These labels describe the profiles identified in the analysis. Their interpretation depends on the features, scaling, and cluster assignments used in the notebook.

## 📊 Power BI Dashboard

The dashboard is available in `ABC_Gold_Insights.pbix`.

### Dashboard highlights

- Monthly purchases and sales.
- Net profit/loss trends.
- Customer segments based on clustering.
- Transaction and pricing patterns.
- KPIs supporting procurement and business analysis.

![ABC Gold Power BI dashboard](https://drive.google.com/uc?export=view&id=1lIFMqXEHvqS3B_j09_v4HjX4M7zuhD7j)

## 🔍 Key Findings

| Focus area | Analytical contribution |
|---|---|
| Price volatility | GARCH analysis examines changes in conditional price volatility. |
| Sales trends | Monthly trends help identify periods of stronger or weaker sales activity. |
| Anomaly detection | LOF highlights unusual observations for further investigation. |
| Customer segmentation | Clustering provides a data-driven view of different purchasing profiles. |
| Procurement planning | Moving averages, market indicators, and seasonal patterns provide additional decision context. |

## 🚀 Recommendations

- Combine price-volatility analysis with business constraints and inventory requirements when evaluating procurement timing.
- Use Bollinger Bands as one analytical indicator rather than a standalone trading or procurement rule.
- Review LOF-flagged transactions before drawing conclusions about irregular activity.
- Use customer segments to investigate opportunities for tailored engagement and retention.
- Incorporate observed seasonal patterns into inventory and promotional planning.

## 📂 Project 1 Files

The original project documentation lists the following deliverables:

| File | Description |
|---|---|
| `Sales Data.csv` | Cleaned, merged sales dataset |
| `Daily Rate Capture.csv` | Cleaned metal-price dataset |
| `GoldBees Data.csv` | GoldBees ETF dataset |
| `Trend_and_Pattern_Analysis.ipynb` | EDA and trend analysis |
| `ML models.ipynb` | Modeling and risk analysis |
| `ABC_Gold_Insights.pbix` | Power BI dashboard |
| `Project report.pdf` | Project report |

*Availability depends on which original project files are included in the combined repository.*
