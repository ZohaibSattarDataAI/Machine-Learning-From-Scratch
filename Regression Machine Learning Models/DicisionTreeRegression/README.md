# ⚡ Decision Tree Regression for Electricity Consumption Prediction using Scikit-learn

This project showcases the use of a **Decision Tree Regressor** to predict electricity consumption based on weather and usage-related features. Built using **Scikit-learn**, this notebook walks through a real-world-style dataset covering environmental and appliance-related attributes, simulating energy usage forecasting in smart homes or industrial IoT systems.

---

## 📘 Project Overview

**Decision Tree Regression** is a powerful non-linear algorithm used for predicting continuous outcomes. In this end-to-end project, we walk through the entire ML workflow, including:

- 📥 Loading and inspecting the electricity consumption dataset  
- 📊 Performing Exploratory Data Analysis (EDA) using Seaborn and Matplotlib  
- ✂ Splitting data using `train_test_split()`  
- 🔧 Preprocessing features with `StandardScaler()`  
- 🌳 Training a regression model using `DecisionTreeRegressor()`  
- 🧪 Hyperparameter tuning for improved performance  
- 📈 Evaluating the model using key regression metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score  
- 🧮 Visualizing the actual vs predicted values  

---

## ⚙️ About the Dataset

The dataset focuses on **electricity consumption forecasting**, where various weather and usage-based features are considered. It includes the following columns:

- 🌡️ `temperature` — Current ambient temperature  
- 💧 `humidity` — Relative humidity levels  
- 🌬️ `wind_speed` — Speed of wind at the time  
- 🧺 `appliance_usage` — Level of home or industrial appliance activity  
- 🕓 `time_of_day` — Time category (e.g., morning, afternoon, night)  
- 🍂 `season` — Current season (Spring, Summer, etc.)  
- ⚡ `electricity_consumption` — Actual energy usage (target feature)  
- 📈 `Prediction` — Target column for regression model  

This kind of dataset is crucial for **smart grid systems**, **energy optimization**, and **IoT-based monitoring**.

---

## ✅ Features Implemented

- Complete data preprocessing pipeline  
- Visualization of trends and outliers  
- Decision Tree modeling with hyperparameters (e.g., max_depth, min_samples_split)  
- Evaluation using MAE, MSE, RMSE, and R²  
- Result visualization through scatter plots  

---

## 🧪 Technologies Used

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Seaborn  
- Matplotlib  

---

## 📂 Use Cases

This project is great for:

- ⚡ Predictive modeling in **energy analytics** and **smart metering**  
- 🌐 Internet of Things (IoT) applications for home and industrial usage  
- 🎓 Academic learning for non-linear regression models  
- 📊 Building ML projects with real-world impact in sustainability and optimization  

---

## 👨‍💻 Author

**Zohaib Sattar**  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)

---

## ⭐ Support the Project

If this project helped you understand Decision Tree Regression or sparked interest in energy forecasting and data science, give it a ⭐ on GitHub and share it with your community. Your support encourages further open-source contributions and innovation in AI! 🚀
