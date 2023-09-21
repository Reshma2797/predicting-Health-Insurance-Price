# Health Insurance Cost Prediction Using Regression

## Abstract
Insurance is a policy that tries to decrease costs incurred by accident or illness.This can be influenced by various factors.
We use different regression techniques to predict the cost of insurance and compare the results.
We compare the results from Linear regression, Lasso regression, Ridge Regression, Polynomial regression, Random Forest Regressor and Decision Tree Regressor.

 [Dataset] Health_Insurance.csv

## Results and Conclusion
| Model        | Mean Squared Error | Mean Absolute Error  | Root mean Squared error |
| ------------- |:-------------:|:-------------:|:-------------:|
|Linear Regression | 0.0334 | 0.1321 | 0.1892 
| Ridge Regression | 0.0334 | 0.1146 | 0.1827  
| Lasso Regression | 0.0572 | 0.1732 | 0.2392    
| Polynomial Regression | 0.0217 | 0.0927 | 0.1475 
| Decision Tree Regression | 0.0504 | 0.1114 | 0.2246 
| Random Forest Regression | 0.0223 | 0.0854 | 0.1493   

The findings can be summarized in the table above , it shows
us that the <b>polynomial regression</b> model fit the best with the
MSE value of 0.0217 and RMSE value of 0.1475
