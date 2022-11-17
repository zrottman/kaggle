# House Prices - Advanced Regressions Techniques

Notebooks for Kaggle's introductory House Prices competion, which I'm working on with my friend [Andrew](https://github.com/andrewmaher). Using a dataset of 81 features, can we predict home sale prices?

## Version 00: Univariate Regression Model
To get our feet wet, we're building a regression model using a single feature that quantifies total above-grade square footage. Because we're just getting our feet wet, we're not submitting this model to the competition--scores are estimated using a cross validation set.
Model: sklearn.linearmodel.LinearRegression  
Estimated Root Mean Squared Error: $57,429.75  
Estimated Kaggle Score: .28394  

## Version 01: Simple Regression Model
Using only features related to home and lot square footage, how accurate a model can we create? Again, we're still just getting our feet wet, so we're not submitting this model to the competition. Scores are estimated using a cross validation set.
Model: XGBRegressor  
Estimated Root Mean Squared Error: $42,194.37  
Estimated Kaggle Score: .20456  

## Version 02: Quick and Dirty Random Forest (all non-null features)
Out of curiosity, we wanted to see what would happen if we put together a quick and dirty model that uses all features with non-null values. As with the last notebook, we're not submitting this one to the competition, so once again we're estimating scores using a cross validation set.
Model: XGBRegressor  
Estimated RMSE: $33,208.80  
Estimated Kaggle Score: .15104  
