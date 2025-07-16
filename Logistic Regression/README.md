# 🏡 Logistic Regression for Customer Home Ownership Prediction using Scikit-learn

This project demonstrates how to implement a **Logistic Regression** classification model using the **Scikit-learn** library to predict whether a customer is likely to purchase a home based on their demographic and financial attributes. It highlights the effectiveness of logistic regression in binary classification problems that are commonly found in real-world business use cases.

---

## 📘 Project Overview

**Logistic Regression** is a fundamental supervised learning algorithm widely used for binary classification tasks. In this notebook, we implement the full machine learning pipeline for classification using Scikit-learn, covering:

- 📥 Load and inspect the customer dataset  
- 📊 Perform Exploratory Data Analysis (EDA) using Seaborn and Matplotlib  
- ✂️ Split the dataset using `train_test_split()`  
- 🔧 Preprocess features using encoding and `StandardScaler()`  
- 🧠 Train a model using `LogisticRegression()`  
- 🔍 Optimize model performance using `GridSearchCV`  
- 📈 Evaluate model using classification metrics:
  - Accuracy Score
  - Precision Score
  - Recall Score
  - F1 Score  
- 🧮 Visualize the Confusion Matrix for model performance breakdown  

---

## 📊 About the Dataset

The dataset contains anonymized customer data with demographic and financial attributes. It is structured for binary classification tasks and includes the following columns:

- 🧑‍🤝‍🧑 **Gender** — Categorical feature representing the customer's gender  
- 👴 **Age** — Numerical feature representing the customer's age  
- 💸 **EstimatedSalary** — Customer’s estimated income  
- 🏠 **Purchased** — Binary target variable (0 = No, 1 = Yes), indicating home ownership  

This dataset is well-suited to demonstrate binary classification models in financial or marketing analytics.

---

## ✅ Features Implemented

- Data loading and initial inspection  
- Null value checks and data cleaning  
- Categorical encoding and feature scaling  
- Exploratory data analysis with visualizations  
- Model training with `LogisticRegression()`  
- Hyperparameter tuning using `GridSearchCV`  
- Model evaluation using accuracy, precision, recall, and F1-score  
- Confusion matrix visualization  

---

## 🧪 Technologies Used

- Python 3.x  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Scikit-learn  

---

## 📂 Use Cases

This notebook is ideal for:

- 📚 Learning how to apply Logistic Regression for binary classification  
- 💼 Predictive analytics for customer behavior (e.g., home buying, churn, loan default)  
- 🧠 Practicing model evaluation and hyperparameter tuning with `GridSearchCV`  
- 🧳 Adding a structured ML classification project to your data science portfolio  

---

## 👨‍💻 Author

**Zohaib Sattar**  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)

---

## ⭐️ Support the Project

If this project helped you understand Logistic Regression or enhanced your ML skills, please consider giving it a ⭐ on GitHub and sharing it with your peers. Your support fuels future open-source contributions and keeps the data science community growing! 🚀
