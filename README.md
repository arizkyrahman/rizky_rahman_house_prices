# House Prices Prediction: Project Overview
- Correlation between features and target on heatmap
- Creating features using mathematical transformations and feature interactions 
- Create a function to automate plotting 4 types of plot for a single numerical variable
- Distribution of top 5 features correlated with Sales Price
- Public leader board will have little less RMSLE than that of on validation data

## EDA
![alt text](https://github.com/arizkyrahman/rizky_rahman_house_prices/blob/main/images/corelation_matrix_house_price_predict.png?raw=true)

## Data Visualization
![](https://github.com/arizkyrahman/rizky_rahman_house_prices/blob/main/images/distribution_of_saleprice_house_predict.png?raw=true)

## Score
Best score in grid search

A public leader board will have a little less RMSLE than that of on validation data because the below error is on validation data when the model is trained/fitted on 67% of the training data because of 3-fold cross-validation. The public leaderboard will have errors on test data when the model is retrained/refitted on 100% of the training data.

RMSLE on training data: 0.0786
RMSLE on validation data: 0.1214

To avoid overfitting: Difference in the performance (Root Mean Squared Log Error) of model on training data and validation data should be minimized.
