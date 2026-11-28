# Data Cleaning and Preprocessing

## Overview
Data cleaning and preprocessing is an important step in this project. The original customer sales dataset contains missing values, duplicate records, inconsistent data formats and invalid values. Python is used to clean and prepare the dataset for further analysis.

## Dataset Details
- **Dataset:** Messy Customer Sales Dataset
- **Original Rows:** 10,200
- **Original Columns:** 12
- **Tools Used:** Python, Pandas and NumPy

## Cleaning and Preprocessing Steps

### 1. Handling Missing Values
- Identified missing values in different columns.
- Filled numerical missing values using median.
- Filled categorical missing values using mode.
- Retained unavailable customer IDs and purchase dates as missing.

### 2. Removing Duplicates
- Identified duplicate records.
- Removed
- 15 completely duplicated rows.

### 3. Correcting Data Types
- Converted date columns into datetime format.
- Converted Age into numeric format.
- Converted Phone Number into string format.

### 4. Standardizing Data
- Standardized Gender values (M, Male, F, Female).
- Removed unnecessary spaces from City names.
- Standardized city and country formats.

### 5. Handling Invalid Values
- Identified invalid age values.
- Handled negative and unusually high purchase amounts.
- Corrected invalid purchase dates.

### 6. Feature Engineering
Created new columns:
- Signup Year
- Signup Month
- Age Group
- Days Between Signup and Purchase
- Days Since Last Purchase

### 7. Filtering and Aggregation
- Filtered customers based on purchase amount.
- Calculated total sales by city.
- Analysed average purchase amount by gender.
- Calculated customer counts by city.

## Final Output
After completing the cleaning and preprocessing steps, the cleaned dataset was saved as:

`cleaned_customer_sales_data.csv`

## Conclusion
The data cleaning and preprocessing process improved the quality and consistency of the customer sales dataset. 
