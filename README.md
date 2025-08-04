# Task1_Elevate
# Task 1 – Data Cleaning and Preprocessing

## 📌 Objective:
Clean and prepare a raw dataset that contains missing values, duplicates, inconsistent formatting, and incorrect data types. This task is a foundational step in the data analysis process.

## 📁 Dataset:
Simulated version of the **Customer Personality Analysis** dataset (inspired by the one available on Kaggle).

## 🔧 Tools Used:
- Python
- Pandas

## 🛠 Steps Performed:

1. **Handled Missing Values**  
   - Filled missing `income` and `year_of_birth` using the **median** of respective columns.

2. **Removed Duplicate Rows**  
   - Detected and dropped duplicate customer entries.

3. **Standardized Text Columns**  
   - Converted `gender` to lowercase.  
   - Converted `country` to title case for consistency.

4. **Date Format Fix**  
   - Converted `dt_customer` to proper `datetime` format using `pd.to_datetime()`.

5. **Renamed Columns**  
   - Standardized all column names to **snake_case** format with no trailing spaces.

6. **Corrected Data Types**  
   - Ensured `income` and `year_of_birth` were stored as `int`.

## ✅ Files Included:

- `task1_cleaned_data.csv` – Final cleaned version of the dataset  
- `task1_cleaning.py` – Python script used for cleaning  
- `task1_raw_data.csv` – Raw (uncleaned) data used as input  
- `README.md` – Project overview and documentation.

## 🙋‍♀️ Interview Prep – Questions to Practice:

- What are missing values and how do you handle them?
- What’s the difference between `dropna()` and `fillna()` in Pandas?
- What is outlier treatment and why is it important?
- How do you handle inconsistent date formats?
- How do you check and maintain data quality?


📌 *This task is a part of the Data Analyst Internship Program.*
