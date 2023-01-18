Feature transformation is a mathematical transformation in which we apply a mathematical formula to a particular column (feature) and transform the values, which are useful for our further analysis. It is a technique by which we can boost our model performance. 

Why Feature Transformation is used?
1. It is mandatory to digitize categorical features for models to work properly. This is called encoding.
2. The scale between features in the dataset can be very different from each other (or they may have different units). For example, while the “Age” feature varies between 0–100, “Car Price” can vary between 0–1000000. Some machine learning methods are affected by these scale differences, so normalizing the difference will contribute to the success of the model.
3. Transformation decreases the effects of outliers since the variability is reduced by scaling.
4. Transformation decreases the effects of outliers since the variability is reduced by scaling.
5. Some machine learning models are based on the assumption that the features are normally distributed. However, in real-life problems, the data is usually not normally distributed. In this case, we apply transformations to approximate these skewed data to the normal distribution so that the models can yield better results.

Some of the Feature Engineering techniques are :-
1. Handeling missing values
2. Handeling categorical features
3. Outlier Detection
4. Feature Scaling
