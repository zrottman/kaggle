# House Prices - Advanced Regressions Techniques

Notebooks for Kaggle's introductory House Prices competion, which I'm working on with my friend [Andrew](https://github.com/andrewmaher). Using a dataset of 81 features, can we predict home sale prices?

## Version 01: Simple Regression Model
Using only features related to home and lot square footage, how accurate a model can we create? (Because we're just getting our feet wet, we're not submitting this model to the competition, so we estimated scores using a cross validation set.)
Model: XGBRegressor
Estimated Root Mean Squared Error: $35,443.19
Estimated Kaggle Score: .19677

## Version 02: Quick and Dirty Random Forest (all non-null features)
Out of curiosity, we wanted to see what would happen if we put together a quick and dirty model that uses all features with non-null values. As with the last notebook, we're not submitting this one to the competition, so once again we're estimating scores using a cross validation set.)
Model: XGBRegressor
Estimated RMSE: $24,244.39
Estimated Kaggle Score: .127166
