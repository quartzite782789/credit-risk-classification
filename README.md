# credit-risk-classification
 Challenge 20

 ChatGPT, Copilot, and classmate assistance were used in the code generation and output interpretation.

 # Purpose

 The purpose of the analysis was to use the dataset to create a model that could predict the creditworthiness of borrowers.

 # Results

 ## Accuracy

The model correctly predicted the loan status for 99% of the test cases. This is a highly accurate model overall

## Precision:

For class 0 (likely representing low credit risk): 1.00

For class 1 (likely representing high credit risk): 0.86

The model was 100% successful identifying those with a low credit risk and not as successful identifying high risk borrowers with a precision of 86%.


## Recall:

For class 0: 0.99

For class 1: 0.94

This means the model correctly identified 94% of the actual high-risk borrowers and 99% of the low risk borrowers.

# Summary

Overall the model has a high success rate. The model is close to perfect in identifying low risk borrowers. This means that those in this category are highly likely to repay borrowed amounts.

On the other hand the model is not as accurate with high credit risk borrowers. It sometimes classifies a low risk borrower as high risk and may result in loans being denied though the likelihood of repayment is high.

It does catch 94% of high risk borrowers.

Due to the model's ability to accurately identify low credit risk borrowers and correctly identify 94% of high risk borrowers, I would recommend use of this model.
