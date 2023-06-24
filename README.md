# Online-Payments-Fraud-Detection

The dataset consists of financial transaction information, including the transaction type, amount, sender and recipient details, balances, and fraud status.

Several engineered features were created to analyze the transactions, such as transaction count by sender, receiver's fraud transaction count, and discrepancies in transaction amounts.

Two models, Logistic Regression and Random Forest, were trained using different hyperparameter settings.

Using Logistic Regression with different alpha values, the log loss was consistently low across all alpha values, indicating good model performance.

For Random Forest, the cross-validation log loss was also extremely low for different combinations of n_estimators and max depth values, demonstrating excellent predictive capability.

Logistic Regression: The log loss values range from 0.09 to 0.1 for different alpha values.

Random Forest: The log loss values range from 5.42898e-05 to 5.47549e-05 for different combinations of n_estimators and max depth.

Random Forest and Tree based models led to overfit issues.
