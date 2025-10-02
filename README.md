# Combined-Cycle-Power-Plant-CCPP-_Using_Multiple_Linear_Regression_Python
Calculating MSE and RMSE of Combined Cycle Power Plant (CCPP) dataset using Multiple Linear Regression

This project is about selecting the best model for our CCPP dataset. Based on the analysis, below are the results :


Comparison of RMSE Value using LinearRegression = Root Mean Squared Error: 4.44226285844249. 
The RMSE value is still within the acceptable range because it's Relative Error is lesser than 1%. Specs within 10%-15% are still acceptable.

If we drop AP and RH, we are getting even worst results as below :

Mean Squared Error: 23.50970822077997

Root Mean Squared Error: 4.848681080539322

DecisionTreeRegressor = Root Mean Squared Error: 4.748588631545224

DecisionTreeRegressor (after tuned)= Root Mean Squared Error: 3.9117326809388953

RandomForestRegressor = Root Mean Squared Error: 4.172839386333255

RandomForestRegressor (after tuned) = Root Mean Squared Error: 3.2106233015617343

So, RandomForestRegressor (after tuned) have smaller differences (smaller RMSE value) about 3.2106233015617343. Using DecisionTreeRegressor (after tuned) can be considered too but with the max_depth 15 too, this is because the overall data is 9568 (approximately 10K).

