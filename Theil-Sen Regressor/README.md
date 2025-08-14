# 📊 Theil-Sen Regression for Robust Predictive Modeling

This is my [21]th project in the field of Machine Learning and Regression Modeling.

This project demonstrates how to implement a **Theil-Sen Regressor** — a robust regression technique ideal for handling outliers and noisy datasets — to predict target variables based on multiple real-world features.  
It showcases a complete regression pipeline — from data exploration to model training and evaluation — offering a strong foundation for solving prediction tasks in industries such as healthcare, finance, environmental science, and engineering.

---

## 📘 Project Overview

**Theil-Sen Regression** is a non-parametric method that estimates the slope as the **median of slopes** between all possible pairs of sample points.  
This approach makes it significantly more resistant to outliers compared to traditional Ordinary Least Squares regression.

In this notebook, we walk through the end-to-end regression process, covering:

- 📥 Loading and inspecting the dataset  
- 🔍 Performing Exploratory Data Analysis (EDA) using Seaborn and Matplotlib  
- 🧼 Preprocessing and scaling features where necessary  
- ✂ Splitting the dataset using `train_test_split()`  
- 🧠 Training a regression model using `TheilSenRegressor()`  
- 📈 Evaluating the model using regression metrics:  
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  

- 📊 Visualizing predicted vs. actual values with regression and scatter plots  

---

## 📊 About the Dataset

The dataset is inspired by real-world use cases where robust regression is necessary due to noise or the presence of extreme values. It includes:

- 📢 **Domain-Specific Indicators** — Numerical variables representing measurable real-world factors  
- 📉 **Target Variable** — Continuous numerical variable representing the prediction goal  

The dataset simulates industry situations where accuracy and resilience to anomalies are critical for decision-making.

---

## ✅ Features Implemented

- Data loading and inspection  
- Missing value checks and statistical summaries  
- EDA with boxplots, pairplots, and correlation heatmaps  
- Model training with Theil-Sen Regression  
- Model performance evaluation using MAE, MSE, RMSE, and R²  
- Visualization of predicted vs. actual values  

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

- 📚 Learning how to implement robust regression models  
- 📈 Predictive analytics in finance, healthcare, and environmental monitoring  
- 🧠 Handling datasets with outliers effectively  
- 🧳 Building a strong data science portfolio project  

---

## 👨‍💻 Author

**Zohaib Sattar**  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)  

---

## ⭐ Support the Project

If this project helped you understand robust regression modeling or enhanced your data science skills, please consider giving it a ⭐ on GitHub and sharing it with your peers.  
Your support encourages more open-source contributions and helps grow the ML community! 🚀
