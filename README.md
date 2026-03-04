# 📊 HR & Project Data Analysis – Python Capstone Project

## 📌 Project Overview

Built a structured analytical dataset from multiple HR and project files using Python and Pandas.  Cleaned, merged, and automated business rules with custom logic and aggregated project cost reports.  Delivered an analysis-ready master dataset with 100% accuracy evaluation for problem-solving and structure.

This capstone project focuses on building a clean, structured, and analysis-ready dataset by processing multiple raw HR and project-related data files using Python.

The objective was to simulate real-world business data processing by performing data cleaning, transformation, merging, automation of HR rules, and cost aggregation using Pandas and NumPy.

---

## 📂 Dataset Details

The project uses three primary datasets:

1. **Employee Dataset**
   - ID
   - Name
   - Gender
   - City
   - Age

2. **Seniority Level Dataset**
   - ID
   - Designation Level (1 = Highest, 4 = Lowest)

3. **Project Dataset**
   - ID
   - Project Name
   - Project Cost
   - Status (Finished / Ongoing / Failed)

All datasets were exported as CSV files and reloaded for structured processing.

---

## 🧹 Data Cleaning & Processing

- Handled missing values in the Project Cost column using custom running-average logic (implemented via for-loop).
- Split name column into First Name and Last Name.
- Removed redundant columns and standardized data formats.
- Merged multiple datasets into a consolidated master DataFrame.
- Applied conditional logic to automate HR designation updates.
- Removed ineligible employees based on business constraints.

---

## ⚙ Business Logic Implementation

- Added 5% performance bonus for successfully completed projects.
- Demoted designation level for failed projects.
- Promoted employees above age 29 using conditional rules.
- Removed employees exceeding designation level eligibility.
- Generated automated validation checks.

---

## 📊 Aggregation & Reporting

- Calculated total project cost per employee.
- Created a new summary DataFrame: `TotalProjCost`.
- Filtered employees based on city name conditions.
- Produced a reliable master dataset ready for reporting and analysis.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Jupyter Notebook
- CSV File Handling

---

## 📈 Skills Demonstrated

Data Cleaning  
Data Wrangling  
Data Transformation  
Conditional Logic Implementation  
Loop-Based Computation  
DataFrame Merging  
Feature Engineering  
Aggregation & GroupBy  
Business Rule Automation  
Analytical Dataset Creation  

---

## 🎯 Project Outcome

Successfully built a clean and structured master dataset from multiple raw inputs while automating business rules and reporting logic.

The project received 100% positive evaluation for:
- Accuracy
- Logical structuring
- Problem-solving
- Code organization

---

## 👨‍💻 Author

Ankur Chowdhury  
Aspiring Data Analyst | Python | SQL | Excel | Power BI
