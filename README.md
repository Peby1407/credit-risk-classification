# credit-risk-classification


## Overview of the Analysis

This analysis had the sole purpose of dividing our hole dataset of loans into healthy and at risk loans.

We had many different types of data for each loan, there was: 
- Loan Size
- Interest Rate
- Borrower Income
- Debt to Income Ratio
- Number of Accounts
- Derogatory Marks
- Total Debt
- Loan Statuts.

All of this information enabled us to create a Linear Regression model and be able to analyze if each loan was a healthy loan  or an at risk loan. And compare it to the provided study that was on column ' Loan_status', where the '0' meant healthy loan and the '1' loan at risk.

In this dataset we have and overly exagerated sample difference for Healthy Loans (75036) and Loans at risk (2500). So in order for us to get a more precise prediction, we did 2 different analysis.
  - The first one was with the original data as given.
  - The second one was with a resampled dataset, with 2500 values each.
  - 
## Results

* Machine Learning Model 1, original values:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
Here we had a 99.18% accuracy, it is a really good result but we thought we could get a better one with a more balanced dataset.


* Machine Learning Model 2, resampled values:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
Here we had a 99.36% accuracy, we can clearly see that the resampled version is better. This might not be a huge difference number wise, but in the banking environment, this 0.18% can mean millions of dollars in jeopardy.

## Summary

In this case we recommend the resampled model, as we mentioned in the previous analysis this 0.18% difference in the banking system can mean the potential loss of millions of dollars in credits uncollected.

We can also recommend to focus more in the '0', as if there is a mistake in the prediction, we could miscategorize some really big loans that should be at risk. Besides, if if has a '1', we will treat it with precaution, and no problem will emerge from this.
