# Customer-Churn-Prediction-with-SHAP
Customer Churn Prediction using Random Forest and SHAP Explainability

## Project Workflow

Dataset → Data Cleaning → EDA → Feature Engineering → Random Forest → SHAP Explainability → Business Insights

# Customer Churn Prediction with Explainable AI (SHAP)

## Project Overview

This project predicts customer churn in a telecom company using Machine Learning and Explainable AI (XAI).

A Random Forest classifier was trained on customer demographic, service, and billing information to predict whether a customer is likely to leave the company.

To improve transparency and interpretability, SHAP (SHapley Additive exPlanations) was used to explain model predictions at both the global and individual customer levels.

---

## Business Problem

Customer churn is a major challenge for telecom companies.

Identifying customers who are likely to leave allows companies to take proactive retention measures and reduce revenue loss.

The objective of this project is to:

* Predict customer churn
* Identify important churn-driving factors
* Explain individual customer predictions using SHAP

---

## Dataset

Dataset: IBM Telco Customer Churn Dataset

Number of records: 7043

Target Variable:

* Churn

  * 0 = Customer Stayed
  * 1 = Customer Left

Features include:

* Gender
* Partner
* Dependents
* Tenure
* Contract Type
* Internet Service
* Monthly Charges
* Total Charges
* Online Security
* Tech Support
* Payment Method

---

## Machine Learning Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Encoding
5. Train-Test Split
6. Random Forest Training
7. Model Evaluation
8. Explainability using SHAP
9. Business Insights

---

## Models Used

* Random Forest Classifier
* Logistic Regression (comparison model)

---

## Results

Random Forest Accuracy: 79.9%

Top Influential Features:

1. TotalCharges
2. MonthlyCharges
3. tenure
4. Contract
5. PaymentMethod

---

## Evaluation Metrics

* Accuracy
* Classification Report
* Confusion Matrix

Random Forest Accuracy: 79.9%

---

## Explainable AI (SHAP)

SHAP was used to:

* Understand global feature importance
* Explain individual predictions
* Identify factors contributing to customer churn

Visualizations generated:

* SHAP Summary Plot
* SHAP Feature Importance Plot
* SHAP Waterfall Plot

---

## Project Structure

Customer-Churn-Prediction-with-SHAP/

data/

notebook/

images/

README.md

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* SHAP

---

## Conclusion

The Random Forest model achieved approximately 80% accuracy in predicting customer churn.

SHAP explainability provided insights into the key factors influencing churn decisions and enabled transparent interpretation of machine learning predictions.
