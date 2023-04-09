                                                          Polynomial Raegression

Polynomial Regression is a regression algorithm that models the relationship between a dependent(y) and independent variable(x) as nth degree polynomial.
Polynomial regression is a form of Linear regression where only due to the Non-linear relationship between dependent and independent variables we add some polynomial terms to linear regression to convert it into Polynomial regression.

Why Polynomial Regression?

In simple linear regression algorithm only works when the relationship between the data is linear But suppose if we have non-linear data then Linear regression will not capable to draw a best-fit line and It fails in such conditions. Hence, we introduce polynomial regression to overcome this problem, which helps identify the curvilinear relationship between independent and dependent variables.
If we apply a linear model on a linear dataset, then it provides us a good result as we have seen in Simple Linear Regression, but if we apply the same model without any modification on a non-linear dataset, then it will produce a drastic output. Due to which loss function will increase, the error rate will be high, and accuracy will be decreased.

Suppose we have X as Independent data and Y as dependent data. Before feeding data to a mode in preprocessing stage we convert the input variables into polynomial terms using some degree.
Consider an example my input value is 35 and the degree of a polynomial is 2 so I will find 35 power 0, 35 power 1, and 35 power 2 And this helps to interpret the non-linear relationship in data.

The equation of polynomial becomes something like this :-

y= b0+b1x^1+ b2x1^2+ b2x1^3+...... bnx1^n.

Types of Polynomials :-
1. Linear ---> ax + b = 0
2. Quadratic ---> ax^2 + bc + c = 0
3. Cubic ---> ax^3 + bx^2 + cx + d = 0

The degree of order which to use is a Hyperparameter, and we need to choose it wisely. But using a high degree of polynomial tries to overfit the data and for smaller values of degree, the model tries to underfit so we need to find the optimum value of a degree

Assumptions in polynomial regression:-
1. The behaviour of a dependent variable is explained by a linear, or curvilinear, additive relationship between the dependent variable and a set of k independent         variables (xi, i=1 to k).
2. The relationship between the dependent variable and any independent variable is linear or curvilinear.
3. The independent variables do no depend on each other too.
4. The errors are independent, normally distributed with mean zero and a constant variance.
