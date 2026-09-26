# Retail Sales — Exploratory Data Analysis

An end-to-end EDA on a retail sales dataset, uncovering trends, outliers, and business-relevant patterns to support data-driven decisions.

## Overview

This project explores a retail transactions dataset to answer practical business questions: which products and regions drive revenue, how sales behave over time, and what data quality issues need to be handled before trusting the numbers. The analysis is done end-to-end in a single Jupyter notebook, from raw data to business recommendations.

## Dataset

- **Source:** Retail sales CSV
- **Size:** 4,310 rows, 21 columns
- **Contents:** Transaction-level records including order date, product/category, quantity, price, and customer/location details

## Data Cleaning

Real-world messiness was handled explicitly rather than hidden:
- Mixed casing in categorical fields (e.g. gender) standardized
- Inconsistent date formats parsed into a single consistent format
- Blank/incomplete rows identified and handled
- A significant outlier order (which was inflating Q1 revenue figures) investigated and addressed

## Analysis

The notebook is organized into 9 sections covering:
- Data overview and structure checks
- Univariate analysis (distributions of key numeric and categorical fields)
- Bivariate/multivariate analysis (sales by category, region, and time)
- Trend analysis over time (monthly/quarterly patterns)
- Outlier detection and investigation
- Correlation checks between key variables

## Key Business Recommendations

The analysis produced four data-backed recommendations covering areas such as inventory focus, seasonal planning, and revenue concentration by product/category. See the notebook for the full reasoning behind each.

## Tools and Libraries

- Python
- pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Project Structure

```
DataAnalytics-L1-EDARetailSales/
├── README.md
├── retail_sales_eda.ipynb
└── data/
    └── retail_sales.csv
```

## How to Run

1. Clone the repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn jupyter`
3. Open `retail_sales_eda.ipynb` in Jupyter Notebook
4. Run all cells in order

## Author

Prerna Desai
