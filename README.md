## Employee Salary Analysis (EDA) – San Francisco (FY 2014-15)

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the San Francisco Employee Compensation Dataset for the Fiscal Year 2014–2015.

The primary objective was to clean, analyze, and visualize salary data to uncover insights into employee compensation, outliers, and salary distribution across departments.

---
# Desciption

An Exploratory Data Analysis of the dataset of San Francisco Employee Compensation for Fiscal Year 2014-15 obtained from Agency and data analysis was performed . After extensive cleaning, filtering and manipulation using R, SAS and Advanced Excel to detect potential outliers, the dataset was reduced to 83946 observations and 18 variables to probe into the statistics and draw insightful information using MS-SQL. The results of analysis are presented graphically for better data-visualization using Tableau?

---
# 🛠 Tools & Technologies

R → Data cleaning, filtering, manipulation

SAS → Statistical analysis, anomaly detection

MS Excel (Advanced) → Preprocessing, pivoting, data shaping

MS-SQL → Query-based analysis

Python (Jupyter Notebook) → Documentation and analysis flow

---

# 📊 Dataset

Source: San Francisco Employee Compensation (FY 2014-15)

Initial Size: ~100K+ records

Final Size (after cleaning): 83,946 observations and 18 variables

The dataset includes details such as:

Employee ID

Job title

Department

Base pay, overtime pay, other pay

Benefits and total compensation

---

# 🔍 Key Steps

Data Cleaning & Preprocessing

Removed duplicates and missing values

Detected and handled potential outliers

Standardized salary-related fields

Exploratory Data Analysis

Salary distribution across departments

Pay gaps between job categories

Identifying top-paying roles

Benefits vs. base pay contribution

Visualization (Tableau)

Interactive dashboards for better insights

Department-wise salary comparisons

Trends in total compensation

----

# 📈 Insights

Outliers were identified in extremely high compensation records.

Benefits contributed a significant portion of total compensation in some roles.

Certain departments had noticeable disparities in overtime pay.

---
# 🚀 How to Use

1. Clone this repository:

```bash
git clone https://github.com/your-username/employee-salary-analysis.git

cd employee-salary-analysis

jupyter notebook "EDA -Employee Salary Report.ipynb"
