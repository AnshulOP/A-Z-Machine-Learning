                                                            Univariate Imputation
Univariate imputation is a simple method to deal with missing data in a dataset. In this method, missing values in a given column or variable are imputed with a single estimated value. This estimation is made based on the available values of the same variable in the rest of the observations.

For example, if we have a column with missing values in a dataset, the univariate imputation technique will calculate the mean, median, or mode of the available values in the same column, and then replace the missing values with the calculated estimate. This process is repeated for every missing value in the column.

The univariate imputation technique is straightforward and easy to implement, making it a popular choice for handling missing data. However, it does have some limitations. For example, it does not account for any relationships between variables, so the imputed values may not accurately reflect the true relationship between variables. Additionally, it can lead to biased estimates if the missing data is not missing at random.

In general, univariate imputation is a good option when the missing data is missing at random and the proportion of missing data is low. In other cases, more advanced imputation methods, such as multiple imputation or predictive modeling, may be more appropriate.                                                              
