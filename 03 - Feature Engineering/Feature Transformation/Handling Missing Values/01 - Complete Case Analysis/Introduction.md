                                                            Complete Case Analysis
Complete case analysis (also known as listwise deletion) is a  simple method for handling missing data in a dataset. It is so named because it involves deleting or removing any observations or samples that have any missing values. This can be useful in some cases where the amount of missing data is relatively small and the missing values are believed to be missing at random, meaning that they are missing independently of the other variables in the dataset. In this situation, the samples with missing values might not be that important to the overall analysis, and removing them may not significantly impact the results.

However, complete case analysis can also introduce bias into the analysis if the missing values are not missing at random. For example, if the missing values are related to the outcome variable, or if they are related to other variables in the dataset, removing the samples with missing values may lead to incorrect conclusions about the relationship between the variables. In such cases, complete case analysis should be avoided and more sophisticated methods for handling missing data should be used instead.

Advantages :
1. Easy to implement as no data manipulation required.
2. Preserves variable distribution (if data is MCAR(Missing Completely At Random), then the distribution of the variables of the reduced dataset should match the distribution in the original dataset.

Disadvantages :
1. It can exclude a large fraction of the original dataset (if missing data is abundant).
2. Excluded observations could be informative for the analysis (if data is not missing at random).
3. When using our models in production, the model will not know how to handle missing data.
