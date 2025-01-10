# Machine Learning Model for Customer Churn Prediction
 This project provides a web application for predicting customer churn using machine learning techniques. The application allows users to input various features related to a customer, such as tenure, contract type, and service usage, and receive predictions on whether the customer is likely to churn along with the confidence percentage of the prediction.

![image](https://github.com/user-attachments/assets/f94abec0-600e-4003-960c-799c593d99b3)


## Objective 
 The objective of this project is to analyze a telecommunications customer churn dataset and predict whether a customer is likely to churn (leave the service) based on various features. By employing advanced machine learning techniques, this project aims to provide actionable insights and improve customer retention strategies for the telecom industry.

## Steps and Workflow

### 1. Exploratory Data Analysis (EDA):
 Conducted a comprehensive EDA on the customer churn dataset to uncover patterns and relationships between features.
 Visualized key trends and correlations to identify significant predictors of churn.
 
### 2. Model Development:
 Initially implemented a Decision Tree Classifier to predict churn.
 Improved the model by switching to a Random Forest Classifier, which performed slightly better in terms of accuracy and generalization.
 Conducted hyperparameter tuning for the Random Forest model to further enhance its performance.

### 3. Model Saving:
 Saved the trained Random Forest model using joblib for future predictions without retraining.

### 4. Flask Integration:
 Developed a web application using Flask to make the model accessible via a user-friendly interface.
 Users can input customer details and receive predictions about whether the customer is likely to churn, along with the confidence level of the prediction.

## Hosted Web Application
 The project is hosted online at the following link:
 [http://your-pythonanywhere-username.pythonanywhere.com](https://amirkhan024.pythonanywhere.com/)
