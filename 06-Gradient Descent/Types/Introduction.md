                                                          Types of Gradient Descent
Gradient descent is an optimization algorithm used to find the minimum of a function by iteratively adjusting its parameters. There are several types of gradient descent algorithms, including:

1. Batch Gradient Descent: This is the most common type of gradient descent. It updates the parameters after processing the entire training set. Batch gradient descent can be slow and computationally expensive for large datasets, but it guarantees convergence to a minimum.

2. Stochastic Gradient Descent: Unlike batch gradient descent, stochastic gradient descent updates the parameters after processing each individual training example. This makes it faster than batch gradient descent, but it may not converge to the global minimum due to its noisy updates.

3. Mini-batch Gradient Descent: This is a compromise between batch and stochastic gradient descent. It updates the parameters after processing a small subset of the training set, called a mini-batch. This allows for faster convergence than batch gradient descent while maintaining stability during updates.
