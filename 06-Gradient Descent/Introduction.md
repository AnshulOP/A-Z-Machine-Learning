                                                              Gradient Descent
Gradient descent is a first-order optimization algorithm that can be used to find the local minimum of a cost function. The cost function is typically a measure of the error between the predicted output of a model and the actual output. The basic idea behind gradient descent is to update the parameters of the model in the direction of the negative gradient of the cost function. The negative gradient of the cost function tells us the direction in which the function is decreasing the fastest.

The general steps of the gradient descent algorithm are as follows :

1. Initialization: The first step is to initialize the parameters of the model with some values. These values can be chosen randomly or using some predefined values.

2. Compute the cost function: The next step is to compute the cost function for the current values of the parameters. This cost function tells us how well the current model is performing. The goal is to minimize this cost function.

3. Compute the gradient: After computing the cost function, we need to compute the gradient of the cost function with respect to each of the model parameters. The gradient is a vector that points in the direction of the steepest increase of the cost function.

4. Update the parameters: Using the gradient, we update the parameters of the model. The update rule is given by : new_parameters = old_parameters - learning_rate * gradient, where learning_rate is a hyperparameter that controls the step size of the algorithm. The learning rate needs to be carefully chosen to ensure that the algorithm converges to the minimum of the cost function.

5. Repeat: We repeat steps 2-4 until the cost function converges to a minimum or some other stopping criterion is met.

There are two main types of gradient descent: batch gradient descent and stochastic gradient descent.

Batch gradient descent updates the model parameters using the average of the gradients computed over the entire training set. This can be computationally expensive for large datasets, but it guarantees convergence to the global minimum.

Stochastic gradient descent updates model parameters using the gradient computed for a single training example. This is computationally less expensive, but the update direction may be noisy and may not always converge to the global minimum. A variant of stochastic gradient descent called mini-batch gradient descent updates the parameters using a small subset of the training data at a time, which is a compromise between batch and stochastic gradient descent.                                                          
