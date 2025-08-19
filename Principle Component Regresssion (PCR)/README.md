# 📊 Principal Component Regression (PCR) for Dimensionality Reduction & Predictive Modeling  

This is my **[22]th project** in the field of **Machine Learning and Regression Modeling**.  

This project demonstrates how to implement **Principal Component Regression (PCR)** — a technique that combines **Principal Component Analysis (PCA)** with regression modeling to handle **multicollinearity** and reduce dimensionality — to predict target variables based on multiple real-world features.  

It showcases a complete regression pipeline — from **data exploration to model training and evaluation** — offering a strong foundation for solving prediction tasks in industries such as **finance, healthcare, marketing, and engineering**.  

---

## 📘 Project Overview  

**Principal Component Regression (PCR)** leverages PCA to extract uncorrelated features (principal components) and then fits a regression model on these components.  
This approach:  
- ✅ Reduces noise  
- ✅ Improves interpretability  
- ✅ Mitigates instability when predictors are highly correlated  

### 🔑 End-to-End Workflow in this Notebook:  
- 📥 **Loading and inspecting the dataset**  
- 🔍 **Exploratory Data Analysis (EDA)** using *Seaborn* and *Matplotlib*  
- 🧼 **Preprocessing and scaling features**  
- ✂ **Splitting the dataset** using `train_test_split()`  
- 🧠 **Training** a regression model with `Pipeline([Scaler → PCA → LinearRegression])`  
- 📈 **Evaluating the model** using:  
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  
- 📊 **Visualizations**: explained variance ratios & predicted vs. actual values  

---

## 📊 About the Dataset  

The dataset simulates real-world scenarios where predictors are **interrelated**, leading to **multicollinearity**. It includes:  
- 📢 **Feature Variables** — Numerical indicators with correlations among them  
- 📉 **Target Variable** — Continuous numerical variable representing the prediction goal  

---

## ✅ Features Implemented  

- Data loading and inspection  
- Missing value checks and statistical summaries  
- EDA with correlation heatmaps and variance plots  
- Dimensionality reduction using PCA  
- Model training with Linear Regression on principal components  
- Model performance evaluation (MAE, MSE, RMSE, R²)  
- Visualization of explained variance & prediction accuracy  

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
- 📚 Learning how to implement **Principal Component Regression**  
- 📈 Predictive modeling where features are highly correlated  
- 🧠 Reducing dimensionality for large feature spaces  
- 🧳 Building a strong **data science portfolio project**  

---

## 👨‍💻 Author  

**Zohaib Sattar**  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)  

---

## ⭐ Support the Project  

If this project helped you understand **dimensionality reduction** and **regression modeling**, please consider giving it a ⭐ on GitHub and sharing it with your peers.  

Your support encourages more open-source contributions and helps grow the ML community! 🚀  
