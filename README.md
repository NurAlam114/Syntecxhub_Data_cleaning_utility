# Syntecxhub_Data_cleaning_utility

# 📊 Industrial Data Cleaning Pipeline using Python

## 🔍 Project Overview
This project focuses on cleaning a raw business dataset using Python and Pandas.  
The dataset contains real-world issues such as missing values, duplicate rows, inconsistent formats, and incorrect data types.

The goal of this project is to transform messy raw data into a clean, structured, and analysis-ready dataset.

---

## 🧠 Problem Statement
Raw business data often contains:
- Missing values
- Duplicate records
- Inconsistent text formatting
- Mixed date formats
- Invalid numerical values

This project solves these problems through a step-by-step data cleaning pipeline.

---

## ⚙️ Tools & Technologies
- Python 🐍
- Pandas
- NumPy
- Jupyter Notebook

---

## 📂 Dataset
A simulated business dataset was used, which mimics real-world data issues such as:
- Missing values
- Duplicate rows
- Incorrect date formats
- Special characters in numeric fields (e.g., `$`, `*`)
- Invalid entries (e.g., negative quantity)

---

## 🔧 Data Cleaning Steps

### ✔️ 1. Data Loading & Inspection
- Loaded CSV dataset using Pandas
- Checked shape, columns, and data types

### ✔️ 2. Column Standardization
- Converted column names to lowercase
- Removed spaces and special characters

### ✔️ 3. Handling Missing Values
- Filled categorical values with "Unknown"
- Filled numerical values using median

### ✔️ 4. Removing Duplicates
- Identified and removed duplicate rows

### ✔️ 5. Data Type Conversion
- Converted date columns to datetime
- Converted numeric columns to int/float

### ✔️ 6. Cleaning Text Data
- Removed extra spaces
- Standardized text formatting (title case)

### ✔️ 7. Removing Special Characters
- Cleaned `$`, `,`, `*` from numeric columns

### ✔️ 8. Handling Invalid Data
- Removed negative values
- Dropped rows with invalid dates

### ✔️ 9. Feature Engineering
Created new columns:
- `career_length`
- `gross_sales`
- `discount_amount`
- `net_sales`
- `order_year`

---

## 📈 Analysis Performed
- Average career length
- Category-wise average net sales
- Customers joined before 2020
- Country-wise total sales
- Average rating by country

---

## 📁 Output
- Cleaned dataset exported as CSV
- Data ready for further analysis or visualization

---

## 💡 Key Learnings
- Real-world data is often messy and inconsistent
- Data cleaning is a crucial step before analysis
- Handling edge cases improves data quality significantly

---

## 🚀 Future Improvements
- Add automation using pipeline functions
- Build a CLI tool for reusable cleaning
- Create a dashboard using Streamlit
- Add data validation rules

---

## 👨‍💻 Author
Md. Nur Alam


