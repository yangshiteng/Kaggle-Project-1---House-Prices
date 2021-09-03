# Kaggle-Project-1---House-Prices

# Project Background:

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

This is the Kaggle project which aims to fit a good model to predict the price of each house with 79 explanatory variables

The model will be evaluated by the metric 'Root-Mean-Square-Error' (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.
(Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

# File Descriptions:

train.csv - the training set

test.csv - the test set

data_description.txt - full description of each column

# Exploratory Data Analysis

1. Boxplot
2. Scatterplot
3. Histogram
4. Correlation

# Feature Engineering

1. Skewness Correction
2. Fill Missing Values
3. Create New Features 
4. Feature Transformation
5. Encode Categorical Features

# Model Training

1. 12-fold Cross Validation
2. 7 models: ridge, svr, gradient boosting, random forest, xgboost, lightgbm regressors, StackingSVRegressor
3. Blending all these 7 models to get more robust predictions



