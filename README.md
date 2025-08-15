# Credit-Card-Fraud-Detection
Exploratory data analysis and dashboarding on a credit card transactions dataset to identify fraud patterns
# Credit Card Fraud Detection – EDA & Feature Engineering

## Overview
Performed exploratory data analysis on a credit card transactions dataset to uncover fraud patterns, engineer useful features, and prepare the data for further modeling or dashboarding.

---

## Tools
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- pandasql (SQL queries on DataFrames)
- Power BI (Interactive dashboard)

---

## Key Steps
1. Loaded and cleaned dataset, checked nulls & class distribution.
2. Visualized fraud vs non-fraud trends and correlations.
3. Engineered features:
   - **Hour** (from transaction time)
   - **Amount_log** (log-transformed transaction amount)
4. Queried data using SQL for fraud statistics.
5. Saved cleaned dataset (`cleaned_creditcard.csv`).
6. Built a Power BI dashboard for fraud insights.

---

## Key Insights
- Fraud transactions make up **~0.172%** of the dataset.
- Time-of-day patterns can help detect suspicious activity.
