# Text Cleaning Basics using Pandas

## 📌 Project Overview

This project demonstrates basic text cleaning and data quality checks using Python and Pandas.

A customer dataset containing names, cities, and email addresses was cleaned by removing unnecessary whitespace and standardizing the formatting of customer names.

## 🎯 Objectives

- Remove leading and trailing whitespace
- Remove multiple spaces between words
- Convert customer names to uppercase
- Check for unusual spelling
- Check for missing values
- Check for duplicate records
- Save the cleaned dataset separately

## 🛠️ Tools & Technologies

- Python
- Pandas
- Google Colab
- CSV

## 📂 Dataset

The dataset contains the following columns:

| Column | Description |
|---|---|
| Customer_ID | Unique customer identifier |
| Name | Customer name |
| City | Customer city |
| Email | Customer email address |

## 🧹 Text Cleaning Process

The `Name` column was cleaned using Pandas string functions.

### Cleaning operations:

1. Removed leading and trailing spaces using `.str.strip()`
2. Converted names to uppercase using `.str.upper()`
3. Replaced multiple internal spaces with a single space using `.str.replace()`

Example:

| Before Cleaning | After Cleaning |
|---|---|
| `  john smith` | `JOHN SMITH` |
| `MARY JOHNSON  ` | `MARY JOHNSON` |
| `  david   brown` | `DAVID BROWN` |
| `ROBERT   WILSON` | `ROBERT WILSON` |

## 🔍 Data Quality Checks

The cleaned dataset was checked for:

- Unusual spelling
- Missing values
- Duplicate records

### Results

- No obvious unusual spelling was identified during manual review.
- Missing values: **0**
- Duplicate records: **0**

## 📁 Project Files

- `Text_Cleaning_Basics.ipynb` — Complete Google Colab notebook
- `customer_dataset.csv` — Original dataset
- `customer_cleaned.csv` — Cleaned dataset
- `before_after_examples.csv` — Before-and-after cleaning examples

## 📊 Outcome

The customer names were successfully standardized and the dataset was checked for common data quality issues. The cleaned dataset is ready for further analysis.


Vrinda S Nair

BCA Student | Aspiring Data Analyst | Data Science Enthusiast
