                                                  Gradient Descent (some extra points)
1. Gradient descent is an iterative optimization algorithm used to find the optimal parameters for a machine learning model.
2. Gradient descent works by iteratively adjusting the parameters of the model in the direction of the negative gradient of the cost function, until the cost function is minimized.
3. The cost function represents the difference between the predicted output of the model and the true output, and is used to evaluate how well the model is performing.

In the context of gradient descent, the slope and intercept of a linear regression model can be found using the following formulas:

1. Slope formula: The slope of the line can be calculated as the partial derivative of the cost function with respect to the slope parameter:

        slope = (1/m) * sum((h(x) - y) * x),
        where m is the number of training examples, h(x) is the predicted value of the model for input x, y is the true output for input x, and x is the input feature.

2. Intercept formula: The intercept of the line can be calculated as the partial derivative of the cost function with respect to the intercept parameter:

        intercept = (1/m) * sum(h(x) - y),
        where m is the number of training examples, h(x) is the predicted value of the model for input x, and y is the true output for input x.

3. Update rule: To update the values of slope and intercept during the gradient descent process, we use the following formulas:

        slope = slope - learning_rate * slope_derivative,
        intercept = intercept - learning_rate * intercept_derivative,
        where learning_rate is the hyperparameter that controls the step size in the direction of the negative gradient, and slope_derivative and intercept_derivative           are the values obtained from the above formulas for slope and intercept.                                                 
