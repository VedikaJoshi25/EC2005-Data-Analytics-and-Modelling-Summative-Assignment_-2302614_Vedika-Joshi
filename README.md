# EC2005 Data Analytics and Modelling Assignment

**Repository Link:** https://github.com/VedikaJoshi25/EC2005-Data-Analytics-and-Modelling-Summative-Assignment_-2302614_Vedika-Joshi/blob/main/Summative_Assessment_2302614_Vedika_Joshi.ipynb

## Overview

The analysis is carried out entirely in Jupyter Notebooks. The project is divided into the following parts:

1. **Data Preparation:**  
   - Filter and clean the dataset to retain only the required variables.
   - Rename variables (e.g., change `inquiries_last_12m` to `credit_checks`).
   - Report the number of observations before and after cleaning, along with summary statistics.

2. **Exploratory Data Analysis (EDA):**  
   - Calculate descriptive statistics for key variables (interest rate, annual income, debt-to-income, loan amount).
   - Generate frequency tables for categorical variables (grade, verified_income, homeownership).
   - Create and interpret visualizations such as histograms, scatterplots (with regression lines), and boxplots.

3. **Regression Analysis:**  
   - Estimate five regression models:
     - **Model 1:** Simple regression with debt-to-income.
     - **Model 2:** Simple regression with a bankruptcy dummy.
     - **Model 3:** Regression with dummy variables for verified income (using “Not Verified” as the reference category).
     - **Model 4:** Multiple regression including debt-to-income, credit utilization, and bankruptcy dummy.
     - **Model 5:** Enhanced multiple regression with additional variables (annual_income, loan_amount, term, grade, emp_length, homeownership, loan_purpose, credit_checks) along with appropriate dummy variables.
   - Report regression equations, interpret coefficients, and perform hypothesis testing.

4. **Presentation and Discussion:**  
   - Organize regression results into comprehensive tables (including standard errors, significance levels, R², sample size, and F-statistics).
   - Interpret the findings and discuss potential improvements to the model specification.
   - Discuss the extent to which the results can be interpreted as causal relationships.

