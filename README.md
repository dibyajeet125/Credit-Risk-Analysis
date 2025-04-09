# Credit-Risk-Analysis
Credit Risk Analysis: Analyzed 373,028 loan records, identifying 332,250 (89%) Good Loans and 40,778 (11%) Bad Loans. Built predictive models to estimate Probability of Default (PD) and calculated Expected Loss (EL) using advanced feature engineering and machine learning techniques.


This project focuses on analyzing credit risk using a comprehensive dataset of loan records. The goal is to build a predictive model that estimates the probability of default (PD) for borrowers and calculates the Expected Loss (EL) for a lending institution. By identifying key risk factors and quantifying potential losses, this analysis aims to provide actionable insights for optimizing lending strategies and minimizing financial risk.

Key Highlights

Dataset: The analysis is based on 373,028 loan records, each described by 339 features.

Objective: Develop a robust model to distinguish between Good Loans (332,250 loans, 89%) and Bad Loans (40,778 loans, 11%).

Data Preprocessing:

Handled missing values in critical features such as emp_title, mths_since_last_record, and desc to ensure data integrity.

Converted categorical variables (e.g., loan grades A-G) into numerical formats for machine learning compatibility.

Feature Engineering:

Created new features like dti (Debt-to-Income ratio) buckets and mths_since_last_record intervals to improve model accuracy.

Machine Learning:

Built a predictive model to estimate the Probability of Default (PD) for each loan.

Expected Loss Calculation:

Implemented Expected Loss (EL) calculations using the formula:

EL = PD × Exposure at Default (EAD) × Loss Given Default (LGD)


Structure
Data Loading and Exploration: Loading the datasets using pandas and exploring key variables.

Data Cleaning and Preprocessing: Handling missing values and converting categorical features.

Feature Engineering: Creating new features to enhance model performance.

Model Development: Building and training a machine learning model to predict loan defaults.

Expected Loss Calculation: Implementing the EL formula to quantify potential losses.
