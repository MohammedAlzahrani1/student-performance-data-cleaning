# Student Performance Data Cleaning Project – Excel

## Overview
This project focuses on **cleaning and organizing student performance data** from two public high schools in Portugal:  
- **Gabriel Pereira (GP)**  
- **Mouzinho da Silveira (MS)**  

The dataset includes information such as:  
- School  
- Age  
- Reason for choosing the school  
- Mother's education level (Medu)  
- Father's education level (Fedu)  
- Other student performance-related data  

The main goal of this project is to **prepare the data for analysis** using Excel techniques like sorting, filtering, filling missing values, and converting text data to numeric format.

---

## Project Files
This repository contains **two files**:

1. **Raw Data (Before Cleaning)**  
   - This file contains the original dataset as collected, before any modifications.  
   - Filename: `student_performance_raw.csv`

2. **Cleaned Data (After Cleaning)**  
   - This file contains the dataset after all cleaning steps, including:  
     - Removing invalid ages  
     - Filling missing values in the "Reason" column  
     - Converting Medu and Fedu columns from text to numeric values  
   - Filename: `student_performance_clean.csv`

> Including both files clearly demonstrates the difference between raw and cleaned data and documents the cleaning process.

---

## Data Cleaning Steps

1. **Organize Columns**  
   - If all data is in a single column, use **Text to Columns** in Excel to separate data into proper columns.

2. **Sort by School and Age**  
   - Identify age ranges for each school  
   - Detect invalid ages

3. **Clean Ages**  
   - Remove any student outside the age range **15–19**

4. **Fill Missing Values**  
   - In the "Reason" column, replace blank cells with `none_given`

5. **Convert Text to Numeric**  
   - Convert Medu and Fedu columns using the following mapping:
     - No Education → 0  
     - Primary Education → 1  
     - 5th–9th Grade → 2  
     - Secondary Education → 3  
     - Higher Education → 4

6. **Final Verification**  
   - Ensure all columns are clean, complete, and ready for statistical analysis or machine learning.

---

## Expected Output
- A clean dataset with properly organized columns, no invalid ages, no missing values, and numeric data ready for analysis.  
- The cleaned dataset can be used for calculating averages, performance metrics, or further analysis.

---

## Tools Used
- **Microsoft Excel** 

---

### Author
**Mohammed Muteb Alzahrani**
