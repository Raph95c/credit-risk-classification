# credit-risk-classification

# Activity 
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

# Questions
## How well does the logistic regression model predict both the `0` (healthy loan) and `1` (high-risk loan) labels?
- The logistic regression model shows us a high accuracy at 100% for '0', and for '1' at 85% which is a high accuracy.

## How well does the logistic regression model, fit with oversampled data, predict both the `0` (healthy loan) and `1` (high-risk loan) labels?
- The oversampled model generated an accuracy score of 99% which turned out to be higher than the model fitted with imbalanced data. The reason is that it performs better because it does a good job in catching mistakes such as labeling non-healthy (high-risk) loans as healthy (low-risk)
