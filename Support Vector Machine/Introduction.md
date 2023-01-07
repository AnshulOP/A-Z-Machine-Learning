Support Vector Machine(SVM) is a supervised machine learning algorithm used for both classification and regression. Though we say regression problems as well its best suited for classification. The objective of SVM algorithm is to find a hyperplane in an N-dimensional space that distinctly classifies the data points. The dimension of the hyperplane depends upon the number of features. If the number of input features is two, then the hyperplane is just a line. If the number of input features is three, then the hyperplane becomes a 2-D plane.

What are Hyperplane and Support Vectors?

1. There can be multiple lines/decision boundaries to segregate the classes in n-dimensional space, but we need to find out the best decision boundary that helps to classify the data points. This best boundary is known as the hyperplane of SVM.
2. The data points or vectors that are the closest to the hyperplane and which affect the position of the hyperplane are termed as Support Vector. Since these vectors support the hyperplane, hence called a Support vector.

SVM can be of two types:

1. Linear SVM: Linear SVM is used for linearly separable data, which means if a dataset can be classified into two classes by using a single straight line, then such data is termed as linearly separable data, and classifier is used called as Linear SVM classifier.
2. Non-linear SVM: Non-Linear SVM is used for non-linearly separated data, which means if a dataset cannot be classified by using a straight line, then such data is termed as non-linear data and classifier used is called as Non-linear SVM classifier.

In this case where our data is non-linear we cannot find a straight line to separate our data. So how can we solve this problem by using the Kernel Trick.
A kernel is a method of placing a two dimensional plane into a higher dimensional space, so that it is curved in the higher dimensional space. (In simple terms, a kernel is a function from the low dimensional space into a higher dimensional space.

Types of SVM Kernels :-
1. Polynomial Kernel Function - The polynomial kernel is a general representation of kernels with a degree of more than one. It’s useful for image processing.
K(xi,xj) = (xi.xj)d, where ‘.’ is the dot product of both the numbers and d is the degree of the polynomial.
2. Gaussian RBF Kernel Function - RBF is the radial basis function. This is used when there is no prior knowledge about the data.
K(xi,xj) = exp(-γ||xi – xj||)2
3. Sigmoid Kernel Function - This is mainly used in neural networks. We can show this as:
K(xi,xj) = tanh(αxay + c)
4. Hyperbolic Tangent Kernel Function - This is also used in neural networks. The equation is:
K(xi,xj) = tanh(kxi.xj + c)
5. Linear Kernel Function
This kernel is one-dimensional and is the most basic form of kernel in SVM. The equation is:
K(xi,xj) = xi.xj + c


