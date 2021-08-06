# Credit-Fraud-Detection

In this analysis we try to discern between normal and fraudulent credit card payments. Our intial dataset is very imbalanced because of the 284,807 transactions it contains only 492 are fradulent this is something that we need take into account while creating our prediction model. We first look at some basic graphs and create a correlation matrix from the whole dataset. We then create a new dataframe with a sample of the normal data and all of the fraudulent transactions. This way our new dataframe contains 492 normal and 492 fraud transactions. We show a new correlation matrix for this dataframe. After that we create a logistic regression model to predict if a new transaction is fraudulent or not.
