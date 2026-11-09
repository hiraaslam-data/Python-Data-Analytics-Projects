# Cafe Sales Data Cleaning

A data cleaning project in Python (pandas) on a messy cafe sales dataset. The notebook turns the raw, dirty data into a clean CSV that is ready for analysis.

**Notebook:** `Cafe_Sales_Data_Cleaning.ipynb`
**Input:** `dirty_cafe_sales.csv`
**Output:** `cleaned_cafe_sales.csv`

## What this project does
1. Loads the raw data and checks its structure and missing values (`info()`, `isnull().sum()`)
2. Replaces placeholder text (`ERROR`, `UNKNOWN`) with proper missing values (NaN)
3. Converts `Quantity` and `Total Spent` to numeric, `Transaction Date` to datetime, and `Transaction ID` to string
4. Removes duplicate rows
5. Detects and removes outliers using the IQR method (on `Quantity` and `Total Spent`)
6. Builds a before/after comparison table (total rows, missing values, duplicates)
7. Saves the cleaned dataset to CSV
8. Bonus: a small sentiment analysis demo on sample customer reviews (TextBlob), shown as a bar chart

## Tools & libraries
Python, pandas, NumPy, matplotlib, TextBlob

## How to run
```bash
pip install pandas numpy matplotlib textblob
jupyter notebook Cafe_Sales_Data_Cleaning.ipynb
```
Place `dirty_cafe_sales.csv` in the same folder as the notebook (update the file name in the first cell if yours differs).

## Skills shown
Data cleaning, handling missing values, data type correction, outlier detection (IQR), before/after validation
