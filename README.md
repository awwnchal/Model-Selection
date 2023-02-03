

#Model-Selection

For the heart.csv dataset (Dependent variable: heart_attack), choosed a sample subset (after removing missing value, nulls, empty columns) of this dataset. Consider when selecting a training subset from the above dataset (such as balanced distribution between training and test for the treated observations), Randomly splitted the dataset into test and training sets using 80% observations as training set. Fitted a simple linear regression model (full model) to predict the heart attack probability and test your model against the test set.  Explained the model and obtained the R^2 for the predictions of the test data set (i.e., a true OOS R^2).
 
Used the training set and estimated an 8-fold cross-validation to estimate the R^2 of the full model. e., use cross-validation to train (on 7/8 of the training set) and evaluate (on 1/8 of the training set).  Calculated the mean R^2 from the 8-fold cross-validation and compare it with the earlier R^2.
 
Fitted a Lasso regression to predict the heart attack probability. Used cross-validation again to obtain lambda_min as well as lambda_1se and chose the simpler model without compromising on the predictive power.
