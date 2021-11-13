# Geny--ML-project
ML Model to Find burn of Respective Employees 
I cacluated Burn out Rate with help of Month of Joining, Gender, Company type, Designation, Resource Allocation and Mental Fatigue Score
  1. Before beginning with Machine Learning I have analysed the data and have done data pre processing.
  2. All the dates were of year 2008 so I have used th concept of feature engineering to add a new feature with the month as date and year will be insignificant.
  3. The missing data with NaN values is replaced using ffill method which used to fill the missing value in the dataframe. ‘ffill’ stands for ‘forward fill’ and will propagate        last valid observation forward.
  4. I have replaced all infinity values with NaN and then with 0 since such huge data will affect the model.
  5. I used linear regression to build the model.
  6. I have used skicit learns libraries to perform linear regression and have added the predicted values of burn rate in the test data set.
