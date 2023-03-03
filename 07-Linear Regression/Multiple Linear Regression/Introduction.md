                                                         Multiple Regression

Multiple linear regression (MLR), also known simply as multiple regression, is a statistical technique that uses several explanatory variables to predict the outcome of a response variable. The goal of multiple linear regression is to model the linear relationship between the explanatory (independent) variables and response (dependent) variables. In essence, multiple regression is the extension of ordinary least-squares (OLS) regression because it involves more than one explanatory variable.

The multiple regression model is based on the following assumptions:
1. There is a linear relationship between the dependent variables and the independent variables.
2. The independent variables are not too highly correlated with each other.
3. yi observations are selected independently and randomly from the population.
4. Residuals should be normally distributed with a mean of 0 and variance σ.

The formula for a multiple linear regression is:

1. y = {beta_0} + {beta_1{X_1}} + … + {beta_n{X_n} + {epsilon}

2. y = the predicted value of the dependent variable

3. beta_0 = the y-intercept (value of y when all other parameters are set to 0)

4. beta_1(X_1) = the regression coefficient (B_1) of the first independent variable (X_1) (a.k.a. the effect that increasing the value of the independent variable has on the predicted y value)

5. … = do the same for however many independent variables you are testing

6. beta_n(X_n) = the regression coefficient of the last independent variable

7. epsilon = model error (a.k.a. how much variation there is in our estimate of y)

To find the best-fit line for each independent variable, multiple linear regression calculates three things:

1. The regression coefficients that lead to the smallest overall model error.

2. The t statistic of the overall model.

3. The associated p value (how likely it is that the t statistic would have occurred by chance if the null hypothesis of no relationship between the independent and dependent variables was true).
