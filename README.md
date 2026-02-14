# End-to-End Ecommerce Data Cleaning & Validation Pipeline

## Project Overview
This project focuses on cleaning and preprocessing an ecommerce sales dataset using **PostgreSQL** and **Python (pandas, psycopg2)**.  
The goal is to transform raw, inconsistent data into a clean, analysis-ready format.

## Dataset
- Source: Kaggle (E-commerce Dataset)
- Records: ~51,000 rows
- Features include sales, profit, discount, shipping cost, customer details, and order information.

## Tools & Technologies
- PostgreSQL
- Python (pandas, psycopg2, matplotlib)
- Jupyter Notebook

## Data Cleaning Steps

### SQL (PostgreSQL)
- Trimmed whitespace from categorical columns
- Handled missing values:
  - Filled missing numerical values using **mean**
  - Filled missing categorical values using **mode**
  - Replaced remaining NULLs with appropriate defaults

### Python (pandas)
- Loaded cleaned data from PostgreSQL
- Verified data types
- Analyzed skewness of numerical features
- Detected outliers using the **IQR method**

## Key Findings
- No extreme skewness observed in numerical features
- No significant outliers detected after cleaning
- Dataset is fully cleaned and ready for analysis or modeling

## Conclusion
This project demonstrates practical data cleaning skills using both SQL and Python, highlighting the ability to work with real-world messy data and prepare it for analysis.

## Future Work
- Exploratory Data Analysis (EDA)
- Feature engineering
- Predictive modeling
