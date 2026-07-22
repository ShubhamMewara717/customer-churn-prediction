# Data Preprocessing Report

## Problems Found

- TotalCharges stored as object
- Blank spaces in TotalCharges
- customerID is not useful for prediction
- Multiple categorical columns

## Solutions Applied

- Converted TotalCharges to numeric
- Converted invalid values into NaN
- Removed missing rows
- Removed customerID
- Encoded categorical variables using One-Hot Encoding

## Why These Solutions?

- Numeric datatype is required for calculations.
- Only 11 rows had missing values, so removing them had minimal impact.
- customerID does not contribute to prediction.
- Machine Learning models require numerical inputs.

## Final Dataset Shape

(7032, 31)

## Remaining Issues

No missing values.
No object columns.
Dataset is ready for Machine Learning.