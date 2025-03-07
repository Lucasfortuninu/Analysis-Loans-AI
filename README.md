# Loan Eligibility Analysis with Machine Learning

## 📌 Description
This repository contains a loan eligibility analysis based on **machine learning**. The goal is to predict whether an applicant is eligible for a loan based on various financial and personal attributes.

This project was developed as a final project for the **Machine Learning** course in the **third year** of the **Computer Engineering** degree at the **Universidad Pública de Navarra (UPNA)**.

## 🏆 Project Objectives
- Evaluate the **eligibility of an applicant** for receiving a loan.
- Apply **data preprocessing** techniques to improve the dataset's quality.
- Train and compare different **classification models**.
- Evaluate the **interpretability** of the selected model.

## 🚀 Technologies Used
- **Python** 🐍
- **Pandas and NumPy** for data manipulation.
- **Scikit-learn** for modeling and evaluation.
- **Matplotlib and Seaborn** for data visualization.
- **Jupyter Notebook** for the analysis development.

## 📂 Project Contents
1. **Dataset selection and motivation**.
2. **Exploration and treatment of the dataset**.
3. **Data splitting into training and testing sets**.
4. **Comparison of different classification models**.
5. **Model explainability**.
6. **Conclusions and future improvements**.

## 📊 Models Evaluated
Different classification models were compared, including:
- **Logistic Regression**
- **Naive Bayes**
- **Neural Networks**
- **Decision Trees**
- **Random Forest**
- **Ensemble Methods (Bagging, Boosting)**

The best-performing model was **Decision Trees**, with an accuracy of **98.47% on the test set**.

## 🔍 Model Explainability
- It was identified that the **CIBIL score** is the most influential feature in the prediction.
- The **loan duration** also plays a key role.
- It is recommended to balance the classes to improve the fairness of the model.
