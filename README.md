The purpose of this credit risk assessment is to test the precision and accuracy of a supervised learning model that can predict the creditworthiness of borrowers.

The data used for this exercise was historical lending activity from a peer-to-peer lending services provider

The desired prediction value was proper categorization of “Healthy Loans” and “High-risk Loans” based on several features: loan size, interest rate, income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.

This exercise utilizes LogisticRegression algorithm to make predictions. It also utilizes a confusion matrix and a classification report to help interpret results.

Results:

The model did well in predicting healthy loans and high-risk loans. Based off the classification report I would recommend this model for use by the company. Below is my analysis.

Accuracy: 99% accuracy. Near perfect model.

Precision: The high-risk loan predictions had a higher margin of error. It only had 500 samples to test, but still had a precision of 89%. Healthy loans had a lot more samples to test so maybe that's why the precision and f1-scores are almost perfect. 

Recall score: The healthy loans had a perfect recall score, meaning the actual positives were correctly classified. The high-risk loans had a recall score of 93% which is still pretty good.
