                                                       Support Vector Regression

Support Vector Regression is a supervised learning algorithm that is used to predict discrete values. Support Vector Regression uses the same principle as the SVMs. The basic idea behind SVR is to find the best fit line. In SVR, the best fit line is the hyperplane that has the maximum number of points.

Unlike other Regression models that try to minimize the error between the real and predicted value, the SVR tries to fit the best line within a threshold value. The threshold value is the distance between the hyperplane and boundary line.

For large datasets, Linear SVR is used. Linear SVR provides a faster implementation than SVR but only considers the linear kernel. The model produced by Support Vector Regression depends only on a subset of the training data, because the cost function ignores samples whose prediction is close to their target.

Unlike in the Ordinary Least Squares, the SVR model sets a threshold error allowance ϵ around the regression line such that all the data points within ϵ are not penalized for their error. Therefore, the bound is error insensitive and is called ϵ - insensitive tube or simply ϵ - tube.

Data points that fall outside the ϵ-tube are penalized for their error:
1. The error associated with the data point above ϵ-tube is computed as the verticle distance between the datapoint and ϵ-tube’s margin.
2. If the data is below the tube, an error is the verticle distance between the ϵ-tube’s lower bound and the datapoint.

Whenever a data point is above the tube’s margin, the deviation is denoted as ζ and ζ∗ when it is below. Both the ζ and ζ∗ are called Slack Variables.

For linear data basic Linear Kernel equation is used to predict results but if the data present is Non-Linear then the model is used with another kernel fucntions like Radial Basis Function, Polynomial Function, Gaussian Kernel etc.
