# 📊 Huber Regression for Robust Predictions with Outlier Resistance using Scikit-learn

This project demonstrates how to implement a **Huber Regressor** using the **Scikit-learn** library to make accurate predictions even when the dataset contains outliers. It showcases the power of robust regression techniques in real-world scenarios where traditional linear regression may be misled by extreme values.

---

## 📘 Project Overview

**Huber Regression** is a robust regression method that combines the strengths of **L1 (absolute error)** and **L2 (squared error)** loss functions, making it less sensitive to outliers while maintaining good performance on normal data points.

In this notebook, we implement a complete regression pipeline using Scikit-learn, covering:

- 📥 Load and explore the dataset  
- 📊 Perform Exploratory Data Analysis (EDA) with Seaborn and Matplotlib  
- ✂ Split the dataset using `train_test_split()`  
- 🔧 Preprocess features for optimal model performance  
- 🧠 Train models using both `HuberRegressor()` and `LinearRegression()` for comparison  
- 🔍 Evaluate models with regression metrics:  
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  
- 🖼 Visualize regression lines to show how Huber Regression resists outlier influence  

---

## 📊 About the Dataset

The dataset represents a real-world inspired scenario with numerical features and includes an **intentional outlier** to simulate noisy measurements.

Example columns include:

- 📏 **Feature_X** — Main independent variable influencing the target  
- 🎯 **Target_Y** — Dependent variable to be predicted  
- 🚨 **Outlier** — A simulated extreme value that demonstrates Huber’s robustness  

This dataset is designed to clearly illustrate the difference between standard linear regression and robust regression methods like Huber.

---

## ✅ Features Implemented

- Data loading and inspection  
- Outlier simulation for robustness testing  
- Data visualization for trend and outlier detection  
- Model training with `HuberRegressor()` and `LinearRegression()`  
- Regression metrics comparison between models  
- Visual plots showing performance differences  

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

- 📚 Understanding robust regression methods  
- 💼 Building predictive models where datasets contain noisy or extreme values  
- 🧠 Comparing model performance under challenging data conditions  
- 🧳 Adding a practical outlier-handling project to your data science portfolio  

---

## 👨‍💻 Author

**Zohaib Sattar**  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)  

---

## ⭐ Support the Project

If this project helped you understand robust regression or inspired you to try Huber Regression in your own datasets, please give it a ⭐ on GitHub and share it with your network.  
Your support motivates future open-source contributions and strengthens the data science community! 🚀
