# Data Understanding Report

## Dataset Summary

- Total Rows: 7043
- Total Columns: 21

## Numerical Columns

- SeniorCitizen
- tenure
- MonthlyCharges

## Categorical Columns

- customerID
- gender
- Partner
- Dependents
- PhoneService
- MultipleLines
- InternetService
- OnlineSecurity
- OnlineBackup
- DeviceProtection
- TechSupport
- StreamingTV
- StreamingMovies
- Contract
- PaperlessBilling
- PaymentMethod
- TotalCharges
- Churn

## Missing Values

- Check using:
  df.isnull().sum()

## Duplicate Values

- Check using:
  df.duplicated().sum()

## Target Column

- Churn

## First Observations

- Dataset contains customer information.
- Churn is the target variable.
- Most columns are categorical.
- TotalCharges may require cleaning because it is stored as an object.
- customerID should not be used for modeling.