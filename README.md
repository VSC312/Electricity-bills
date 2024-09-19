# **Customer Churn Prediction**
## **Overview**

This project focuses on predicting customer churn for a bank using machine learning techniques. The objective is to identify which clients are likely to leave the bank, enabling proactive measures to retain valuable customers. The project involves exploratory data analysis (EDA), data preprocessing, feature engineering, model training, and evaluation.[Dataset Link](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling/data)

## **Project Structure**

#### **Data Analysis:**

Performed EDA to understand data characteristics and class imbalance.
Visualized feature correlations and distributions.


#### **Data Preprocessing:**

Handled class imbalance using oversampling techniques.
Encoded categorical variables and created new features.
Scaled features using MinMaxScaler.
Managed outliers to optimize model performance.


#### **Modeling:**

Developed a Gradient Boosting Classifier model to predict customer churn.
Tuned hyperparameters using Optuna to achieve optimal performance.
Evaluated the model using F1-score and compared results across training, validation, and test sets.


#### **Feature Importance:**

Analyzed feature contributions using SHAP values to understand key drivers of customer churn.


## **Results**

#### **Model Performance:**

Cross-Validation F1 Score: 95%
Test Set F1 Score: 83%
The model achieved high accuracy in predicting customer churn, with notable features including Age, Balance, NumberOfProducts, and IsActiveMember.

#### **Key Insights:**

Older customers and those with higher balances are more likely to churn.
Active members have a lower likelihood of leaving.
Low credit scores are associated with higher churn rates.


## **Contributing:**

Feel free to contribute !!


## **Contact:**

Email - vsc312@gmail.com
LinkedIn - [Click here](www.linkedin.com/in/vardhan-choudhary)








