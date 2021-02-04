# Assumption Test Guidance Guidance

## General Information

Mainly created to test if the multiple linear regression model for predictive analytics is good enough to be applied on the future datasets (i.e. evaluate the model). There are four types of assumptions tests:
  1. The residuals are <b>Normally Distributed</b>
  2. The residuals are independent of one another <b>(Auto Correlation)</b>
  3. The residuals have equal variances <b>(Heteroskedasticity)</b>
  4. The Independent Variables / Predictors are not correlated with one another <b>(Multicollinearity)</b>
  
Any violation from one of the rules above may indicate a bias on the model. Further info for assumption violation impacts on the model can be check on [here](https://online.stat.psu.edu/stat462/node/145/)

## Assumptions Test Structure

Below is the explanation of assumption test chronology. It will be listed as the following:
  1. Normal Assumption Test - Rejected
  2. Assumption Test Exclude Impression Predictors (In the future will be stated as No Impression) - Rejected
  3. Assumption Test After Outlier 1 and Outlier 2 (No Impression) - Rejected
  4. Assumption Test After Outlier 2 (No Impression) - Accepted
  5. Assumption Test After Outlier 2 + LN Transformation (No Impression) - Rejected
  6. Polynomial Model - Rejected




