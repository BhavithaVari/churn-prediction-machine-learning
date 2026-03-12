# Churn-prediction-machine-learning
## Project Overview

Customer churn prediction is an important problem for telecom companies because acquiring a new customer is often more expensive than retaining an existing one.
The goal of this project is to build a machine learning model that predicts whether a customer will **churn (leave the service)** or **stay** based on customer demographics, services used, and billing information.

---

## Dataset

The dataset used in this project is the **Telco Customer Churn Dataset**.
It contains information about customers such as:

* Customer demographics
* Account information
* Services subscribed
* Billing details
* Churn status

**Number of records:** 7043
**Number of features:** 21

Target variable:

* **Churn**

  * 1 → Customer churned
  * 0 → Customer stayed

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Imbalanced-learn (SMOTE)

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Encoding Categorical Variables
6. Train-Test Split
7. Handling Class Imbalance using SMOTE
8. Model Training
9. Model Evaluation

---

## Machine Learning Models Used

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 81%      |
| Random Forest       | 80%      |
| XGBoost             | 78%      |

Logistic Regression performed best for this dataset.

---

## Model Evaluation

The models were evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report (Precision, Recall, F1-Score)

These metrics help understand how well the model predicts churn and non-churn customers.

---

## Key Insights

* Customers with **month-to-month contracts** have a higher churn rate.
* Customers with **short tenure** are more likely to churn.
* **Higher monthly charges** are associated with higher churn.

---

## Business Impact

The churn prediction model can help telecom companies:

* Identify customers at risk of leaving
* Provide targeted offers or discounts
* Improve customer retention strategies

---

## Future Improvements

* Hyperparameter tuning for better model performance
* Deploy the model using a web application
* Use more advanced models or deep learning approaches
* Use additional customer behavioral data

---

## Author

V.Bhavitha

Machine Learning Project – Customer Churn Prediction
