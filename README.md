# Ames_Housing_Regression_Analysis

In this project, we perform linear regression modelling on the Ames Housing dataset, created in 2011 which features +70 variables describing most aspects of a residential home in Ames (Iowa, U.S), with the objective of predicting property prices.

Before performing regression analysis, data is cleaned and engineered which can be found in data_engineering project notebook. Regression is then performed using OLS, Ridge and Lasso to investigate the performance differences across different linear models.

Through the performed modelling, we find that all three models appear stable with similar R-square, MSE and RMSE values. However, we used OLS as our final model choice to make both predictions and inferences.

Our results show that variables relating to the age, size, condition and qualilty of the property have the largest impact on the price of the property as one may expect. These features are closely followed by the location of the home and the size of the garage, if one is included. In total, we found 18/23 features to be statistically significant with a confidence level of 99%, with a final R-squared value of 0.901.
