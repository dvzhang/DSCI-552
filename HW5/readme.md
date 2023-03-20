# DSCI HW 5
> By Tianzuo Zhang
>
> USC-ID:8849-5991-30
> 
> My contact info: [Twitter](https://twitter.com/dvzhangtz) [Linkedin](https://www.linkedin.com/in/tianzuo-zhang/) Wechat: dvzhangtz

## 1. Decision Trees as Interpretable Models
(a) Download the Accute Inflamations data from https://archive.ics.uci.edu/
ml/datasets/Acute+Inflammations.
(b) Build a decision tree on the whole data set and plot it.1
(c) Convert the decision rules into a set of IF-THEN rules.2
(d) Use cost-complexity pruning to find a minimal decision tree and a set of decision
rules with high interpretability.



## 2. The LASSO and Boosting for Regression
(a) Download the Communities and Crime data3 from https://archive.ics.uci.edu/ml/datasets/Communities+and+Crime. Use the first 1495 rows of data as the training set and the rest as the test set.
(b) The data set has missing values. Use a data imputation technique to deal with
the missing values in the data set. The data description mentions some features
are nonpredictive. Ignore those features.
(c) Plot a correlation matrix for the features in the data set.
(d) Calculate the Coefficient of Variation CV for each feature, where CV =
s
m
, in
which s is sample standard deviation and m is sample mean..
(e) Pick b
√
128c features with highest CV , and make scatter plots and box plots for
them. Can you draw conclusions about significance of those features, just by the
scatter plots?
(f) Fit a linear model using least squares to the training set and report the test error.
(g) Fit a ridge regression model on the training set, with λ chosen by cross-validation.
Report the test error obtained.
(h) Fit a LASSO model on the training set, with λ chosen by cross-validation. Report
the test error obtained, along with a list of the variables selected by the model.
Repeat with standardized4
features. Report the test error for both cases and
compare them.
(i) Fit a PCR model on the training set, with M (the number of principal components) chosen by cross-validation. Report the test error obtained.
