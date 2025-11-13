# 🧹 Data Wrangling Project – Data Science Salaries

This project focuses on cleaning, transforming, and preparing a real-world dataset of Data Science salaries for deeper analysis and modeling. The goal is to turn messy raw data into a consistent, high-quality, analysis-ready dataset.

---

## 🎯 Objective
- Perform data cleaning and preprocessing on the Data Science Salaries dataset.
- Standardize inconsistent salary formats, categorical values, and feature structures.
- Produce a clean dataset suitable for EDA, modeling, and dashboarding.

---

## 📂 Dataset Description
- **3,755 rows**, **11 features**
- Includes job titles, experience level, employment type, company size, country, salary (local + USD)
- Target: **Salary** (numeric, inconsistent formats)
- Contains mixed formatting, missing values, and categorical inconsistencies.

---

## 🛠 Actions Performed
- Inspected dataset (`info()`, `describe()`, missing values, duplicates)
- Cleaned salary columns:
  - Removed text, symbols, currency notations
  - Standardized ranges (e.g., “5jt–7jt” → average numeric value)
- Encoded categorical variables
- Normalized inconsistent labels
- Prepared final clean dataset for modeling

---

## ⭐ Key Insights
- Raw salary data contained multiple inconsistent formats → wrangling was essential.
- Experience level and job title showed early correlation with salary ranges.
- After cleaning, dataset became reliable for EDA, regression, and visualization.

---

## 📦 Tech Stack
Python • Pandas • NumPy • Matplotlib • Seaborn • Google Colab

---

## 🚀 Output
A clean, standardized dataset ready for modeling and data visualization.
