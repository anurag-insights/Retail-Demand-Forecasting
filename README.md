# Retail Demand Forecasting

## Project Overview

This project focuses on developing a data-driven retail demand forecasting system to predict future product demand using historical sales data, calendar variables, promotional activities, pricing, and other relevant factors.

The primary objective is to help retail businesses improve inventory planning, minimize overstocking, reduce stock-outs, and make better purchasing decisions through time-series analysis and machine learning.

## Business Problem

Retail businesses often rely on historical sales records and manual estimations to determine future product demand. This approach can lead to inaccurate inventory decisions.

Two major challenges arise:

- **Overstocking:** Excess inventory increases storage costs and creates the risk of unsold products.
- **Stock-outs:** Insufficient inventory during periods of high demand results in lost sales and customer dissatisfaction.

This project aims to address these challenges by developing forecasting models that estimate future product demand more accurately.

For the detailed business problem, refer to `Business Problem.txt`.

## Project Objectives

- Perform exploratory time-series analysis to identify trends, seasonality, and demand patterns.
- Identify and handle missing values, inconsistent records, incorrect data types, and outliers.
- Engineer time-based features and other relevant predictors.
- Develop forecasting models using historical sales and calendar-related variables.
- Compare forecasting models using MAE, RMSE, and WAPE.
- Provide data-driven insights to support inventory planning.

## Dataset Description

The project uses a synthetic retail sales dataset containing:

- 200 daily observations
- 12 columns
- One fictional retail store
- One fictional beverage product

The dataset intentionally contains data quality issues, including missing values, inconsistent categorical values, incorrect data types, duplicate dates, invalid records, and numerical outliers.

This allows the project to demonstrate realistic data cleaning and preprocessing techniques.

**Note:** The dataset is synthetically generated for educational and portfolio purposes. It does not represent actual business transactions.

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Time-Series Forecasting Techniques
- Jupyter Notebook

## Project Workflow

1. Business Problem Understanding
2. Data Collection and Understanding
3. Data Quality Assessment
4. Data Cleaning and Preprocessing
5. Exploratory Data Analysis (EDA)
6. Time-Series Analysis
7. Feature Engineering
8. Forecasting Model Development
9. Model Evaluation and Comparison
10. Business Insights and Recommendations

## Model Evaluation Metrics

The forecasting models will be evaluated using:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted demand.
- **RMSE (Root Mean Squared Error):** Penalizes larger forecasting errors more heavily.
- **WAPE (Weighted Absolute Percentage Error):** Measures total absolute forecasting error relative to total actual demand.

## Repository Structure

```text
Retail Demand Forecasting/
│
├── data/
│   └── retail_demand_forecasting_raw_data.xlsx
│
├── notebooks/
│
├── outputs/
│
├── Business Problem.txt
│
└── README.md
```

## Outcome

The final outcome is a retail demand forecasting workflow that compares multiple forecasting approaches and identifies a suitable model for predicting future product demand.

The project also demonstrates how forecasting results can support inventory management decisions and reduce the risks associated with overstocking and stock-outs.

