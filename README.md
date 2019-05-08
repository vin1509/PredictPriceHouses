Project Scope:
Predicting the price of each home in Ames, Iowa. Our dataset describes 79 features which can influence prices of residential homes. Keeping in mind the variety of features and how each of them impact the house price, we have selected this dataset.

Motivation & purpose:
The predicted prices will enable residents who intend to purchase a house in Ames to understand the price ranges across different areas of the city
This will also be useful for realtors to pitch their final sale price (after adjusting their commission) to their clients

Dataset:
Continuous Variables – such as linear feet measure of street connected to property, lot size, year built, masonry veneer area in square feet, total square feet of basement area etc.
Categorical Variables – such as basement type, roof materials, lot configuration etc.
Quality Measures – such as external quality, basement quality, external conditions etc.

Model Building
LASSO Regression - Lasso performs L1 regularization which adds a penalty equal to the absolute value of the magnitude of coefficients
Ridge Regression - Ridge performs L2 regularization which adds a penalty equal to square of the magnitude of coefficients
Elastic Net Regression - It is a hybrid of LASSO and Ridge Regression
 
Boosting - Produces a prediction model as an ensemble of weak prediction models - XGBoost, LightGBM
RandomForest - Ensemble of decision trees trained with the bagging method
