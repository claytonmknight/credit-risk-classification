# credit-risk-classification
 ## Overview of the Analysis

The analysis aimed to develop machine learning models to predict loan statuses based on financial information provided in the dataset. The dataset contained features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable was the loan status, with values of `0` for healthy loans and `1` for high-risk loans.

The stages of the machine learning process included:

1. Data preparation: Reading the dataset, separating features and labels, and splitting the data into training and testing sets.
2. Model training: Using logistic regression to train a predictive model on the training data.
3. Model evaluation: Generating a confusion matrix and classification report to assess the model's performance on the testing data.

## Results

* Logistic Regression Model:
    * Accuracy Score: 0.99
    * Precision (0): 1.00
    * Recall (0): 0.99
    * Precision (1): 0.85
    * Recall (1): 0.91

## Summary

The logistic regression model achieved strong performance with an accuracy of 0.99 in predicting loan statuses. It demonstrated perfect precision for healthy loans (`0`) and maintained relatively high precision and recall for high-risk loans (`1`). This indicates its ability to effectively distinguish between healthy and high-risk loans.

However, the optimal model choice depends on the specific goals of the analysis. If the priority is accurately identifying high-risk loans (`1`), the logistic regression model is suitable due to its balanced precision and recall for both labels. Nonetheless, if minimizing false positives (misclassifying healthy loans as high-risk) is important, further exploration of alternative models may be necessary.

In conclusion, the logistic regression model is recommended for its strong overall performance and balanced predictive capabilities. However, careful consideration of the analysis objectives is essential when determining the most suitable model for deployment.