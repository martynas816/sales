# Sales Data Analysis – Sample Sales Dataset

This project explores a sample sales dataset to understand revenue patterns across
time, product lines, countries, and deal sizes. The goal is to demonstrate an
end-to-end exploratory data analysis (EDA) workflow and extract business-relevant
insights.

---

## 1. Project Overview

- **Objective:** Analyze historical sales to identify key revenue drivers and trends.
- **Tech stack:** Python, Pandas, Matplotlib, Jupyter / Kaggle Notebook.
- **Dataset size:** 2,823 orders (2003–2005).

The full analysis is contained in the Jupyter notebook:
`Sales_Data_Analysis.ipynb`.

---

## 2. Dataset

- **Source:** Kaggle – Sample Sales Dataset  
- **Rows:** 2,823 orders  
- **Columns (examples):**
  - `ORDERDATE`, `YEAR_ID`, `MONTH_ID`
  - `PRODUCTLINE`, `DEALSIZE`, `COUNTRY`
  - `SALES`, `QUANTITYORDERED`, `PRICEEACH`

Dates are converted to proper datetime objects to enable time-series analysis.

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

(See the notebook for charts and detailed commentary.)

---

## 5. How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/martynas816/sales.git
   cd sales
