#Task 1 – Data Cleaning and Preprocessing

## Dataset: Mall Customer Segmentation Data

This task involved cleaning and preparing a raw dataset of mall customers using Python (Pandas). The goal was to ensure the dataset was consistent, free of errors, and ready for analysis.


##  Dataset Overview

- **Rows**: 200
- **Columns**: 5
- **Original Format**: CSV
- **Cleaned File**: `cleaned_mall_customers.csv`


## Cleaning Summary

- Checked for missing values → **0 found**
- Removed duplicates → **0 found**
- Standardized column names to lowercase with underscores
- Ensured correct data types:
  - `customerid`: int
  - `gender`: object (string)
  - `age`: int
  - `annual_income_(k$)`: int
  - `spending_score_(1-100)`: int



##  Files Included
- `Mall_Customers.csv`-Original dataset
- `cleaned_mall_customers.csv` – Final cleaned dataset
- `task1.ipynb` – Jupyter notebook with step-by-step cleaning
- `README.md` – Summary of task and steps performed
 
## Tools Used

- Python 3
- Pandas Library
- Google Colab
