                                                        Stochastic Gradient Descent
Stochastic Gradient Descent (SGD) is a widely used optimization algorithm for training machine learning models, particularly in deep learning. It is an iterative method for minimizing the objective function, which measures the difference between the predicted values and the true values in the training data. SGD is a variant of gradient descent that performs the parameter updates using a randomly selected subset of the training data, rather than the entire dataset. This approach is much faster and more scalable than traditional gradient descent, as it allows us to update the parameters in a computationally efficient manner.

The general formula for updating the model parameters in SGD is as follows:

    𝜃 ← 𝜃 − 𝜂 ∇𝜃𝐿(𝜃, x(i), y(i))
    where 𝜃 represents the model parameters, 𝜂 is the learning rate, 𝐿(𝜃, x(i), y(i)) is the loss function that measures the difference between the predicted output       and the true output for a single training example (x(i), y(i)), and ∇𝜃𝐿(𝜃, x(i), y(i)) is the gradient of the loss function with respect to the model parameters.

In other words, at each iteration of the SGD algorithm, we randomly select a subset of training examples (x(i), y(i)), and compute the gradient of the loss function for that subset. We then update the model parameters by taking a step in the direction of the negative gradient, scaled by the learning rate 𝜂.

There are several different loss functions that can be used in SGD, depending on the nature of the problem being solved. Some common loss functions include:

1. Mean Squared Error (MSE): This is a commonly used loss function for regression problems, where the goal is to predict a continuous value. The MSE loss function is given by:

    L(𝜃, x(i), y(i)) = (1/2) * (y(i) - h(x(i), 𝜃))^2, 
    where h(x(i), 𝜃) is the predicted output of the model for input x(i) and model parameters 𝜃.

2. Binary Cross-Entropy (BCE): This is a commonly used loss function for binary classification problems, where the goal is to predict one of two possible outcomes. The BCE loss function is given by:

    L(𝜃, x(i), y(i)) = -y(i) * log(h(x(i), 𝜃)) - (1 - y(i)) * log(1 - h(x(i), 𝜃)), 
    where h(x(i), 𝜃) is the predicted output of the model for input x(i) and model parameters 𝜃.

3. Categorical Cross-Entropy (CCE): This is a commonly used loss function for multiclass classification problems, where the goal is to predict one of several possible outcomes. The CCE loss function is given by:

    L(𝜃, x(i), y(i)) = - ∑ y(i,j) * log(h(x(i), 𝜃)_j), 
    where h(x(i), 𝜃)_j is the predicted probability of the jth class for input x(i) and model parameters 𝜃, and y(i,j) is a binary indicator variable that is 1 if the     true class of input x(i) is j, and 0 otherwise.

In summary, stochastic gradient descent is a powerful optimization algorithm for training machine learning models. By using a subset of the training data at each iteration, SGD is much faster and more scalable than traditional gradient descent. The choice of loss                                                        
