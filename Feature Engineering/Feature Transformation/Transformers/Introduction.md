                                                                 Transformers
Transformers help in changing the overall distribution of the data to very close to normal distribution therfore, increasing the accuracy of the model.
These are effective only when if the algorithm requires normally distributed data to fucntion properly like Linear Regression, Logistic Regression.

There are two types of Transformers :
1. Function Transformers
2. Power Transformers

Function Transformers

Log Transformer :
1. We take log to the base 10 of each value present in the column as transformer paramater.
2. Log Transformer is always applied on rightly skewed data to make it close to a normal distribution curve.

Reciprocal Transformer :
1. Values present in the column are reciprocated i.e if the values are small they will become large in value and if they were large before they will become small now.
2. It may be helpful in some cases in achieving the normal distribution curve but not reliable also at the same time.

Square Transformer : 
1. Values present in the column are squared which brings all the values present almost to the same scale.
2. Square Transformer is always applied on leftly skewed data to make it close to a normal distribution curve.

Power Transformers

Box - Cox Transformer :
1. The exponent variable is called lambda that varies over the range of -5 to 5, and in the process of searching, we examine all values of lambda.
2. Finally we choose the optimal value resulting in the best approximation to a normal distribution for the variable.

Yeo - Johnson TRansformer :
1. This transformation is the adjustment to the Box-Cox transformation, by which we can apply it to negative numbers as well as the values that are zero.
                                                                 
