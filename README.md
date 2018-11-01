# quartic

1. did a simple EDA approach followed by a random forest regressor technique to predict the binary target variable.
   
   removal of null/empty/nan values with median of the corresponding columns
   used heatmap to understand correlation between feature and target variables
   followed a pipleine with imputer and cross validation score to validate the results. 
   feature importance graph to understand if further feature reduction can be done after fitting the model first time.
   ran pipeline 2nd time after doing the feature reduction based on the graph
   
2. running the model without feature reduction, using grid search cv will cause performance bottlenecks

3. if i had more time i would--
    try to understant the correlation between features and target variable more closely
    use grid search cv to search for optimum results
    use a voting classifier to comapre the accuracies of different algorithms against the training and test set
    
    
