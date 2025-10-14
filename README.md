# Wrangler Project: Data Cleaning & Analysis on Salary Dataset

## Project Overview
**Wrangler Project** is a data wrangling and preprocessing notebook focusing on cleaning and preparing salary data for analysis.  
The dataset includes job titles, experience levels, employment types, and salary information across multiple countries and currencies.  

This project demonstrates how to:
- Handle missing and inconsistent data  
- Convert salary currencies into USD  
- Standardize and normalize data columns  
- Explore trends and patterns in salary distribution  
- Prepare data for advanced analytics or modeling  

---

## 🧾 Dataset Description
**Source:** DS Salaries Dataset 

| Column | Description |
|---------|-------------|
| work_year | Year when the salary was paid |
| experience_level | Employee experience level (Junior, Mid, Senior, Executive) |
| employment_type | Employment type (FT, PT, Contract, Freelance) |
| job_title | Employee job title |
| salary | Original salary amount |
| salary_currency | Currency type (USD, EUR, GBP, etc.) |
| employee_residence | Country of employee residence |
| company_location | Company’s location |
| remote_ratio | Ratio of remote work (0 = onsite, 50 = hybrid, 100 = remote) |
| company_size | Company size (S, M, L) |

---

## 🧹 Data Wrangling Steps
1. **Data Inspection**
   - Load dataset with Pandas  
   - Identify missing or duplicate values  

2. **Data Cleaning**
   - Rename columns for readability  
   - Handle null or inconsistent data  
   - Convert data types appropriately  

3. **Feature Transformation**
   - Convert all salaries into USD  
   - Add `adjusted_salary` for better comparison  

4. **Exploratory Data Analysis (EDA)**
   - Explore salary distribution by job role and region  
   - Visualize trends with Matplotlib and Seaborn    

---

## 🧠 Tools & Libraries
- **Python 3.x**
- **Jupyter Notebook**
- **Libraries Used:**
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  

---
