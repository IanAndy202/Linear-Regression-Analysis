The model uses Linear regression to make accuarte predictions on the data.  
Linear regression allows for predicting future values based on the observed data between dependant and independant variables. 

To achieve this the model uses linear_regression.intercept_  to represent the point where the regression line crosses the y-axis.

This intercept is the value of the dependent variable (target) when all the feature values are zero.

The linear_regression.coef_  is used as well to represent coefficients for the change in a dependent variable and a corresponding feature,
holding all other features constant. Though this it also provides the slope 

The data itself is also split into 50:50, 90:10, 80:20, 75:25 for training and testing.

The results themselves produce different RMSE(Root Mean Sqaureroot Error) values which can be used in determining accuracy 

RMSE is important as it tells us what partions for testing and training are best for moel accuracy. As the lower the RMSE number, the more accuarte te model could be

The following are the RMSE numbers for each partion:

50:50 - 4.5

90:10 - 4.012

80:20 - 4.012

75:25 - 4.012

From these observations we can conclude that the 50:50 ratio leads to less odel accuracy as there is less data to be trained on compare to the other ratios 
