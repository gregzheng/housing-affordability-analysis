# Why Has Housing Become Less Affordable Over Time?
### An Exploratory Data Analysis of Housing Affordability in the United States

## Overview

Housing affordability has become one of the most significant economic challenges facing Americans. Over the past several decades, home prices and rental costs have increased substantially, often outpacing household income growth. As a result, purchasing or renting a home has become increasingly difficult for many individuals and families across the country.

The purpose of this project is to investigate the key factors associated with declining housing affordability by combining multiple publicly available datasets covering housing prices, rental prices, household income, interest rates, inflation, housing supply, and demographic trends.

Rather than assuming a single cause, this project aims to use data to explore which variables appear to have the strongest relationship with housing affordability over time.

---

# Business Objective

The objective of this project is to answer the following business question:

> **Why has housing become less affordable over time?**

To answer this question, this project will explore historical housing market trends and analyze how economic, demographic, and financial variables have changed alongside home prices and rental costs.

The ultimate goal is to identify meaningful relationships between these variables and communicate findings through interactive visualizations and a dashboard.

---

# Project Objectives

- Analyze historical trends in home prices and rental prices
- Compare housing costs against household income
- Investigate the relationship between mortgage rates and affordability
- Explore the impact of inflation on housing prices
- Analyze regional differences in affordability across the United States
- Identify which variables appear most strongly associated with declining affordability
- Present findings through an interactive dashboard

---

# Data Sources

This project will combine multiple publicly available datasets from trusted sources.

| Dataset | Source | Purpose |
|----------|--------|----------|
| Zillow Home Value Index (ZHVI) | Zillow Research | Historical home prices |
| Zillow Observed Rent Index (ZORI) | Zillow Research | Historical rental prices |
| American Community Survey (ACS) | U.S. Census Bureau | Median household income and demographics |
| Mortgage Rates | Federal Reserve (FRED) | Historical mortgage interest rates |
| Consumer Price Index (CPI) | Bureau of Labor Statistics | Inflation trends |
| Housing Supply / Building Permits | U.S. Census Bureau | Housing inventory and construction activity |

Additional datasets may be incorporated throughout the project if they provide further insight into housing affordability.

---

# Project Workflow

This project follows a standard analytics lifecycle from data collection to business recommendations.

## 1. Data Collection

- Obtain housing, economic, and demographic datasets from public sources
- Understand each dataset's structure and granularity
- Document metadata and assumptions

---

## 2. Data Cleaning & Preparation

Using **Python (Pandas)**, the raw datasets will be cleaned and standardized.

Tasks may include:

- Handling missing values
- Removing duplicates
- Standardizing column names
- Parsing dates
- Converting data types
- Creating derived features
- Merging datasets
- Validating data quality

---

## 3. Exploratory Data Analysis (EDA)

Perform exploratory analysis to better understand the data and identify trends.

Areas of exploration include:

- Distribution of housing prices
- Rental price trends
- Income growth
- Regional comparisons
- Correlation analysis
- Time series analysis
- Outlier detection

The objective of this phase is to generate hypotheses before drawing conclusions.

---

## 4. Statistical & Business Analysis

Using the cleaned dataset, investigate relationships between housing affordability and variables such as:

- Household income
- Mortgage rates
- Inflation
- Housing supply
- Geographic location
- Population growth

This phase will focus on identifying meaningful trends while distinguishing correlation from causation.

---

## 5. Data Visualization

Create clear visualizations to communicate findings.

Examples include:

- Line charts
- Scatter plots
- Correlation heatmaps
- Geographic maps
- Bar charts
- Time series visualizations

Visualizations will emphasize storytelling rather than simply presenting data.

---

## 6. Dashboard Development

Build an interactive dashboard that allows users to explore housing affordability across different regions and time periods.

Potential dashboard features include:

- Housing price trends
- Rental price trends
- Affordability metrics
- Regional comparisons
- Interactive filtering
- Key performance indicators (KPIs)

---

## 7. Findings & Recommendations

Summarize key insights discovered throughout the analysis.

The final deliverable will answer questions such as:

- Which factors appear most strongly associated with declining affordability?
- Which regions have experienced the greatest changes?
- Have housing costs increased faster than household income?
- How have mortgage rates influenced affordability?
- What limitations exist within the analysis?

---

# Tools & Technologies

This project will primarily utilize the following tools:

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Jupyter Notebook
- Git
- GitHub

Potential future enhancements include:

- Streamlit
- dbt
- Snowflake
- SQL
- Machine Learning
- Predictive Modeling

---

# Repository Structure

```
housing-affordability-analysis/

│
├── README.md
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── src/
│
├── visualizations/
│
├── dashboard/
│
├── docs/
│
└── requirements.txt
```

---

# Future Enhancements

Future iterations of this project may include:

- Machine learning models to predict housing prices
- Housing affordability forecasting
- Automated data ingestion pipelines
- SQL data warehouse
- dbt transformation models
- Interactive Streamlit application
- Cloud deployment

---

# Disclaimer

This project is intended for educational and portfolio purposes.

While the analysis aims to identify meaningful relationships within publicly available data, it does not attempt to establish causal relationships. Housing affordability is influenced by numerous economic, political, and social factors that extend beyond the scope of this analysis.
