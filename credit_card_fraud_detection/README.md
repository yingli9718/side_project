Credit Card Fraud Detection

* Credit Card Fraud Detection dataset hosted on Kaggle

* Goal: to detect fraudulent transactions from the total transactions

1) Understanding the data

* Features are all numerical values, no missing values
* Features V1 to V28 are principle components obtained from PCA, they have been scaled. But we don't know what they stand for.
* Only two columns have feature name: Time and Amount
* Class labels are unblanced, very low default rate 0.172%. Number of total case is 284807 and number of fraud is 492.

2) Techniques

* Handing the exceptional values
* Dealing with imbalanced data (re-sampling)
* using exising various metrics, and defing new metrics to evaluate the model performance
* Logisitic regression
* Simple neural network
* Overfitting
