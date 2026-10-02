# Telecom Customer Churn Prediction

The goal of this project is to predict whether a telecom customer will **leave the company (churn)** based on their information and services.

## Dataset

I used the **Telco Customer Churn** dataset from Kaggle.

It contains information about customers such as:

* Tenure
* Monthly charges
* Total charges
* Contract type
* Internet service
* Payment method
* Phone and other services

## What I did

In this project, I:

1. Loaded and explored the dataset.
2. Checked the data types and missing values.
3. Cleaned the `TotalCharges` column.
4. Removed the customer ID because it is not useful for prediction.
5. Converted the `Yes/No` churn values into `1/0`.
6. Separated the features (`X`) and target (`y`).
7. Split the data into training and testing sets.
8. Scaled numerical features using `StandardScaler`.
9. Converted categorical features using `OneHotEncoder`.
10. Built a **Logistic Regression** model.
11. Built a **Decision Tree** model.
12. Compared their accuracy.
13. Used precision, recall and F1-score to evaluate the models.
14. Created a confusion matrix.
15. Used cross-validation to check the model more reliably.
16. Did a small amount of feature engineering.

## Models Used

* Logistic Regression
* Decision Tree



