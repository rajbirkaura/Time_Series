# Prediction in Time Series Dataset
by Rahul Mishra(102083033)

- Predict values of 5 parameters based on multi-input time series data.

## Input File (DATASET.xlsx)

- Original dataset contains 1009 rows and 15 columns.
- First column denotes each road section.
- Second column denotes the year no. for which parameter values are recorded.
- Columns 3 to 15 represents values for parameters 1 to 13.

## Requirements

- Predict values for Para-9 to Para-13 for tenth year of each road section.
- Create graphs for comparing actual values with predicted values for Para-9 to Para-13.

## Model Used

- Light Gradient Boosting Machine - regression model
- Gradient Boosting: decision trees for regression/classification
- Boosting: came out of the idea of whether a weak learner can be modified to become better

## Metric Used

- RMSE: Root Mean Square Error

  ![](images/RMSE1.jpg)

## Result

Final RMSE = 31.187
