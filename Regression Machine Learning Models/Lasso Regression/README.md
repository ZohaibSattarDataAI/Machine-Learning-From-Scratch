# 🧠 Lasso Regression for Salary Prediction using Scikit-learn

This project demonstrates how to implement a **Lasso Regression** model using the **Scikit-learn** library to predict salary based on years of experience. Lasso is particularly useful for feature selection and reducing model complexity through regularization. This project provides a hands-on approach to understanding how Lasso improves linear regression by penalizing less impactful features.

---

## 📘 Project Overview

**Lasso Regression** (Least Absolute Shrinkage and Selection Operator) is a form of linear regression that adds an L1 regularization term to the loss function. It’s valuable in preventing overfitting and enhancing model interpretability, especially when working with high-dimensional data.

In this notebook, we implement the complete Lasso regression pipeline using Scikit-learn:

- 📥 Load and clean the dataset  
- ✍️ Convert float values to integers for clearer interpretation  
- 📊 Visualize the relationship between experience and salary  
- 🧠 Train the model using `Lasso()` from Scikit-learn  
- 📈 Visualize regression line with actual data  
- 📏 Evaluate model using standard regression metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

---

## 📊 About the Dataset

The dataset is a **synthetic salary dataset** tailored for learning regression techniques. It includes a simple yet meaningful structure that makes it easy to understand the linear relationship between:

- 📅 `YearsExperience` — A continuous numeric variable representing a person’s experience  
- 💰 `Salary` — The target variable that we aim to predict  

While minimal in features, this dataset is ideal for demonstrating how regularized models like Lasso behave.

---

## ✅ Features Implemented

- Data preprocessing and inspection  
- Conversion of float to integer values for simplicity  
- Exploratory Data Analysis (EDA) with visualization  
- Lasso regression model training with Scikit-learn  
- Regression line plotting using Matplotlib  
- Model performance evaluation with MAE, MSE, RMSE, and R²  

---

## 🧪 Technologies Used

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📂 Use Cases

This notebook is perfect for:

- 📚 Understanding how Lasso improves standard linear regression  
- 🧠 Learning the impact of L1 regularization in modeling  
- 🎓 Academic projects and regression-based assignments  
- 💼 Portfolio-building with regression models  

---

## 👨‍💻 Author

**Zohaib Sattar**  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)

---

## ⭐ Support the Project

If this project helped you learn or improve your understanding of regularized regression, consider ⭐ starring the repository and sharing it with others. Your support encourages more open-source contributions to help the data science community grow. 🚀
