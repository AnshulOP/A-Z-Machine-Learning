                                                            Regression Metrics
1. Mean Squared Error (MSE): MSE is a commonly used regression metric that measures the average squared difference between the predicted values and actual values. MSE is expressed as the average of the squared differences between the predicted and actual values. Mathematically, it can be represented as:

       MSE = (1/n) * Σ (y_i - y_hat)^2
       where y_i is the actual value, y_hat is the predicted value and n is the number of samples.

2. Mean Absolute Error (MAE): MAE is another regression metric that measures the average absolute difference between the predicted values and actual values. It is expressed as the average of the absolute differences between the predicted and actual values. Mathematically, it can be represented as:

       MAE = (1/n) * Σ |y_i - y_hat|
       where y_i is the actual value, y_hat is the predicted value and n is the number of samples.

3. Root Mean Squared Error (RMSE): RMSE is the square root of MSE. It measures the average magnitude of the error. It is used to determine the magnitude of the error in terms of the units of the dependent variable. Mathematically, it can be represented as:

       RMSE = sqrt(MSE)

4. R-squared (R2 score): R2 score, also known as the coefficient of determination, is a regression metric that measures the goodness of fit of a model. It measures the proportion of variation in the dependent variable that is explained by the independent variables. The R2 score ranges from 0 to 1, where 1 indicates a perfect fit and 0 indicates that the model explains none of the variation in the dependent variable. Mathematically, it can be represented as:

       R2 score = 1 - (SSres / SStot)
       where SSres is the sum of squared residuals (difference between actual and predicted values) and SStot is the total sum of 
       squares (difference between actual values and mean of actual values).

5. Adjusted R-squared: Adjusted R-squared is an adjusted version of R2 score that takes into account the number of independent variables in the model. It penalizes models with a large number of independent variables that do not improve the goodness of fit. The adjusted R2 score ranges from 0 to 1, where 1 indicates a perfect fit and 0 indicates that the model explains none of the variation in the dependent variable. Mathematically, it can be represented as:

        Adjusted R2 score = 1 - (1 - R2 score) * (n - 1) / (n - k - 1)
        where n is the number of samples and k is the number of independent variables in the model.   
