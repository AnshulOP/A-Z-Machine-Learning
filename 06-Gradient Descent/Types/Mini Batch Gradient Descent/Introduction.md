                                                       Mini Batch Gradient Descent
Mini-batch Gradient Descent is a variation of the Gradient Descent algorithm that updates the model parameters based on a small random subset of the training data, rather than the entire training set. This approach is especially useful when the training set is large, as it can significantly reduce the time and computational resources required to update the model parameters.

Mini-batch Gradient Descent works by dividing the training set into small subsets, called mini-batches. Each mini-batch contains a small number of randomly selected samples from the training set. The algorithm updates the model parameters based on the gradient of the cost function with respect to the samples in the mini-batch. The learning rate controls the step size of the parameter update.

The size of the mini-batch is a hyperparameter that needs to be tuned. A larger mini-batch size results in more stable parameter updates, but it also requires more memory and computational resources. A smaller mini-batch size introduces more noise into the parameter updates, but it can lead to faster convergence and better generalization.

Here is a step-by-step explanation of how mini batch gradient descent works:
1. Initialize the parameters of the model randomly or with some initial values.
2. Compute the cost function using all the training data.
3. Compute the gradient of the cost function with respect to each parameter.
4. Update the parameters by subtracting the product of the learning rate and the gradient from the current values.
5. Repeat steps 2 to 4 until the cost function converges to a minimum.

Mini-batch Gradient Descent is a compromise between Batch Gradient Descent, which updates the model parameters based on the entire training set, and Stochastic Gradient Descent, which updates the parameters based on a single randomly selected sample. Mini-batch Gradient Descent provides a good trade-off between computational efficiency and convergence speed.

The main advantage of Mini-batch Gradient Descent over Stochastic Gradient Descent (SGD) is that it reduces the variance of the parameter updates, which leads to more stable convergence. It also allows the use of efficient matrix operations, which can significantly speed up the computation compared to SGD. Moreover, it provides a better trade-off between computational efficiency and convergence speed compared to Batch Gradient Descent.

In summary, Mini-batch Gradient Descent is a widely used optimization algorithm for training machine learning models, especially when the training set is large. It provides a good trade-off between computational efficiency and convergence speed, and it can be easily parallelized to speed up the computation even further.
