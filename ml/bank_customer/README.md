# Bank customer

## Description

The dataset is about bank's customers.

Here are some explanations about the variables:

- RowNumber: Index of the observation
- CustomerID: Unique Ids for bank customer identification
- Surname: Customer's last name
- CreditScore: Credit score of the customer
- Geography: The country from which the customer belongs
- Gender: Male or Female
- Age: Age of the customer
- Tenure: Number of years for which the customer has been with the bank
- Balance: Bank balance of the customer
- NumOfProducts: Number of bank products the customer is utilizing
- HasCrCard: Binary Flag for whether the customer holds a credit card with the bank or not
- IsActiveMember: Binary Flag for whether the customer is an active member with the bank or not
- EstimatedSalary: Estimated salary of the customer in Dollars
- Exited: Binary flag equal to 1 if the customer closed account with bank and 0 if the customer was retained

**The goal is to perform a binary classification on the variable "Exited".**

## Missions

1. Load the data set.
2. Make a brief explanatory analysis (graphics, statistics, etc.).
3. Separate the data set in train set and test set.
4. Preprocess the data. Use the function "ColumnTransformer" to do that. Explain precisely each step, in particular when you drop, impute or transform the variables.
5. Use the k-NN classifier to perform the classification. Find the best hyperparameters with a brute force technique. Compute classical metrics: recall, precision, F1 score, confusion matrix. Interpret the results.
6. Same question with the Support Vector Machine classifier.
7. Same question with the Linear Discriminant Analysis classifier.
8. Same question with the Logistic Regression classifier.
9. Same question with the Decision Tree classifier.
10. Compare the performances of the previous algorithms.