# DATA-CLEANING-AND-PRE-PROCESSING
## Sales Data Cleaning Project

## Objective
Clean and prepare a raw sales dataset with issues like missing values, duplicates, inconsistent formats, and incorrect data types using Python (Pandas).

## Dataset
- Source: [Kaggle - Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
- File: `sales_data_sample.csv`

## Tools Used
- Python
- Pandas
- Google Colab

## Cleaning Steps Performed
- Removed duplicate rows
- Handled missing values in:
  - `postalcode` (minor)
  - `state`, `territory` (optional fields)
- Standardized text columns (`status`, `country`, `dealsize`)
- Converted `orderdate` to `datetime` format
- Renamed all columns to lowercase with underscores
- Ensured correct data types for all columns

## Outputs
- Cleaned dataset: `cleaned_sales_data.csv`
- Summary of changes included in `data_cleaning_summary.md`
