# Project-1---Sales-Prediction
Author : Erlangga Febrianno

Business Problem :
The purpose of the project is creating a sales projection model based on sales data of product in groceries store

Data:
Source of the data https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

Methods:
- Data Cleaning
  To prepare the data I'm using imputing method. There are two columns that has missing data Item Weight and Outlet Size. For the Item weight I use mean of   weight to replace the missing data and for the Outlet Size I replace it with Medium
  

Model:

For the model I use the Random Forest Regression.
The metrics for the train and the test data are
Train RF Reg
 scores: 
 MAE: 299.30 
 MSE: 184,850.30 
 RMSE: 429.94 
 R2: 0.94
Test RF Reg
 scores: 
 MAE: 780.61 
 MSE: 1,269,536.20 
 RMSE: 1,126.74 
 R2: 0.54
 
 Based on the number the Random Forest regression fit the training data with a high R^2 numnber. Eventhough the test number is not high.
 
Recommendations:
For data cleansing try another method for imputing data. 
Random Forest Regression is one of method that we can use to create a model. To make a comparison we can try another model and compare the result.



Limitations and Next Step:
The limitation of this project is the data sufficiency. A lot of missing data that we have to handle and it might affect the model.

Further Information:
For questions you can reach me through this email: anggafebrianno@gmail.com
 
