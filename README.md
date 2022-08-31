# Ames_Housing_Regression_Analysis

In this project, linear regression modelling is performed on the Ames Housing dataset, created in 2011 which includes +70 variables describing most aspects of a residential home in Ames (Iowa, U.S), with the objective of predicting property prices.

Before performing regression analysis, data is cleaned and engineered which can be found in data_engineering project notebook. Regression is then performed using OLS, Ridge and Lasso to investigate the performance differences across a varity of linear models. Results show that all three models appear stable with similar R-square, MSE and RMSE values. We use the OLS model as our final choice to make both simple predictions and inferences from our data.

Our regression results show that variables relating to the age, size, condition and qualilty of the property have the largest impact on the price of the property as one may expect. These features are closely followed by the location of the home and the size of the garage, if one is included. In total, we find 18/23 features to be statistically significant with a confidence level of 99% and a final model R-squared value of 0.90 .
