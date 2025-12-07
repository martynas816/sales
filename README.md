# Sample Sales Data Analysis

This project explores a sample sales dataset to understand revenue patterns across
time, product lines, countries, and deal sizes. The goal is to demonstrate an
end-to-end exploratory data analysis (EDA) workflow and extract business-relevant
insights.

---

## 1. Project Overview

- **Objective:** Analyze historical sales to identify key revenue drivers and trends.
- **Tech stack:** Python, Pandas, Matplotlib, Jupyter / Kaggle Notebook.

---

## 2. Dataset

- Source: Kaggle – Sample Sales Dataset  
- Size: 2,823 sales line items (2003–2005)
- Key fields:
  - Time: ORDERDATE (converted from text to datetime)
  - Product: PRODUCTLINE, DEALSIZE
  - Geography: COUNTRY
  - Revenue drivers: SALES, QUANTITYORDERED, PRICEEACH

---

## 3. Methods

- Data quality checks (`df.info()`, missing values, category distributions)
- Date preprocessing for time-series analysis
- Grouping and aggregation by:
  - Month and year
  - Product line
  - Country
  - Deal size
- Visualization with Matplotlib (bar charts, line plots)
- Business interpretation and recommendations

---

## 4. Key Insights

- **Seasonality:** Revenue dips in May–July and peaks strongly in Q4.
- **Best year:** 2004 is the top revenue year; 2005 shows a notable decline.
- **Top products:** Classic Cars and Vintage Cars are the main revenue drivers.
- **Top markets:** USA dominates sales, followed by Spain and France.
- **Deal sizes:** Medium deals contribute the largest share of total revenue.

---

## 5. How to View

You can view the full analysis directly here on GitHub, or open the interactive version in Kaggle:

Kaggle Notebook: *https://www.kaggle.com/code/martynasdiugas/sales*  
