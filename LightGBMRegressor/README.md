# 🌾 LightGBM Regressor for Crop Yield Prediction using Scikit-learn

This project demonstrates how to implement a powerful **LightGBM Regressor** to predict agricultural crop yields based on multiple environmental and resource-based features. It highlights the strength of gradient boosting algorithms in handling structured tabular data with high accuracy and efficiency.

---

## 📘 Project Overview

**LightGBM (Light Gradient Boosting Machine)** is an advanced gradient boosting framework designed for speed and performance. In this notebook, we walk through an end-to-end regression pipeline using LightGBM with Scikit-learn integration:

- 📥 Load and explore the agriculture-based dataset  
- 📊 Perform Exploratory Data Analysis (EDA) using Seaborn and Matplotlib  
- ✂ Split the dataset using `train_test_split()`  
- 🔧 Preprocess features using `StandardScaler()`  
- 🧠 Train a model using `LGBMRegressor()`  
- 🔍 Optimize model with different hyperparameters  
- 📈 Evaluate model using key regression metrics:
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  
- 📉 Visualize prediction performance using scatter plots and residual analysis  

---

## 📊 About the Dataset

The dataset includes simulated data related to crop yield prediction, with the following features:

- 🌦️ *rainfall_mm* — Rainfall measured in millimeters  
- ☀️ *sunlight_hours* — Average daily sunlight hours  
- 🌱 *fertilizer_kg* — Fertilizer usage in kilograms per hectare  
- 💧 *water_usage_liters* — Water used for irrigation  
- 🍀 *soil_ph* — Soil pH level (acidity or alkalinity)  
- 🌾 *crop_yield* — Actual crop output per hectare (target variable)

This dataset is highly relevant for agricultural planning, sustainability, and yield forecasting.

---

## ✅ Features Implemented

- Data cleaning and feature preprocessing  
- Heatmap and correlation analysis  
- Feature scaling with `StandardScaler()`  
- Model training with `LGBMRegressor()`  
- Evaluation using MAE, MSE, RMSE, R² Score  
- Final conclusion with business insights  
- Recommendations for model tuning and deployment

---

## 🧪 Technologies Used

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- LightGBM

---

## 📂 Use Cases

This project is ideal for:

- 🌽 Agricultural data science and smart farming applications  
- 📈 Forecasting yields to optimize resource usage  
- 🚜 Machine Learning in sustainability and food supply chain  
- 🧠 Practicing gradient boosting techniques in regression tasks  
- 🧳 Adding a real-world impact ML project to your portfolio  

---

## 👨‍💻 Author

**Zohaib Sattar**  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)

---

## ⭐ Support the Project

If this project helped you understand LightGBM Regression or contributed to your ML learning journey, consider giving it a ⭐ on GitHub and sharing it with your network. Your support helps promote open-source contributions and empowers the data science community! 🚀
