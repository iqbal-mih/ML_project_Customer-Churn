# ML_project_Customer-Churn
# Churn Prediction Analysis

## Overview
This Jupyter notebook contains an analysis of customer churn data. The goal is to explore the dataset, understand customer behavior patterns, and identify factors that contribute to customer churn.

## Key Steps

1. **Data Loading & Initial Exploration**
   - Imported necessary libraries (numpy, pandas, matplotlib, seaborn)
   - Loaded the dataset from 'data.csv'
   - Examined data types and converted 'TotalCharges' to numeric and 'SeniorCitizen' to string

2. **Data Understanding**
   - Displayed statistical summaries of numerical variables (tenure, MonthlyCharges, TotalCharges)
   - Showed sample records from the dataset
   - Checked the distribution of the target variable 'Churn'

3. **Exploratory Data Analysis**
   - Visualized the churn distribution with a pie chart (73.4% stayed, 26.6% churned)
   - Identified class imbalance in the target variable
   - Created box plots to examine distributions of numerical features
   - Separated numerical and categorical features for further analysis

4. **Key Findings**
   - The dataset contains 7043 entries with 21 columns (including customerID, demographic info, service details, and churn status)
   - Numerical features show varying distributions that may need normalization
   - The target variable is imbalanced, which may require special handling in modeling

## Next Steps
This analysis provides a foundation for building predictive models. Future work could include:
- Feature engineering
- Handling class imbalance
- Building and evaluating machine learning models
- Deploying the best-performing model

The notebook demonstrates thorough data exploration and visualization, setting the stage for effective churn prediction modeling.

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

## Dataset
The analysis uses a telecom customer churn dataset containing customer account information and whether they churned (left the service).
