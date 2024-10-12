# Stock Price Prediction

This project focuses on predicting the closing price of stocks and their movements using feature engineering and ensemble methods.

# Model Description
The model predicts the closing price of stocks for a given day and its movement (up or down) based on the opening price, date, and company name.

# Goal
The primary goal is to accurately forecast stock prices and their movements to aid in better investment decisions.

# Models Used
Regression Model: A voting ensemble consisting of Linear Regression and Extra Randomized Trees (scikit-learn's LinearRegression and ExtraTreesRegressor respectively), combining performance and efficiency.
Classification Model: Logistic Regression (scikit-learn's LogisticRegression) to predict the movement (up or down) of stock prices.

# Results
Regressor: Achieved a Root Mean Squared Error (RMSE) of 0.096 on the test dataset.
Classifier: Achieved a 0.993 F1 score on the test dataset.

