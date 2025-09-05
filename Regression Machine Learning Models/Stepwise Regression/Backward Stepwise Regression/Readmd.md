# 📊 Backward Stepwise Regression for Feature Selection & Predictive Modeling  

This is my [23]th project in the field of **Machine Learning and Regression Modeling**.  

This project demonstrates how to implement **Backward Stepwise Regression** — a systematic feature selection technique that starts with all predictors included in the model and iteratively removes the least significant variable at each step until only statistically significant predictors remain.  

It showcases a complete end-to-end regression workflow: from **data preparation and feature selection** to **model training and evaluation**, making it a strong portfolio-ready project for practical business and research applications.  

---

## 📘 Project Overview  

**Backward Stepwise Regression** builds models step-by-step by removing predictors:  
✅ Starts with all available features in the model  
✅ Removes the least significant variable at each step  
✅ Stops when all remaining features significantly contribute to performance  
✅ Produces a compact, interpretable, and accurate model  

This approach is especially useful when dealing with datasets that have many predictors and we want to filter out irrelevant or redundant ones.  

---

## 🔑 End-to-End Workflow in this Notebook  

📥 Loading and exploring the dataset  
🔍 Exploratory Data Analysis (EDA) with Pandas, Seaborn & Matplotlib  
🧼 Data preprocessing & splitting into training/testing sets  
⚡ Feature selection using **Backward Stepwise Regression (SBS)**  
🧠 Model training with **Linear Regression**  
📈 Model evaluation using:  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - Root Mean Squared Error (RMSE)  
   - R² Score  

---

## 📊 About the Dataset  

The dataset simulates real-world conditions where multiple predictors may or may not contribute to predicting a continuous target variable.  

- **📢 Feature Variables** — Multiple independent variables (e.g., experience, education, projects, certifications, hours per week).  
- **📉 Target Variable** — A continuous variable (e.g., salary prediction).  

---

## ✅ Features Implemented  

- Data loading and inspection  
- Exploratory Data Analysis (EDA)  
- Backward Stepwise Regression for feature elimination  
- Model fitting using Linear Regression  
- Evaluation metrics: MAE, MSE, RMSE, R²  
- Visualization of selected features and model performance  

---

## 🧪 Technologies Used  

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- MLxtend (for SequentialFeatureSelector)  

---

## 📂 Use Cases  

This notebook is ideal for:  

📚 Learning **Backward Stepwise Regression** as a feature selection technique  
📈 Building compact and interpretable predictive models  
🧠 Reducing unnecessary predictors to avoid overfitting  
🧳 Adding a professional **data science portfolio project**  

---

## 👨‍💻 Author  

**Zohaib Sattar**  
📧 Email:[Zohaib Sattar](zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com)  

---

## ⭐ Support the Project  

If this project helped you understand **Backward Stepwise Regression** and its role in feature selection, please consider giving it a ⭐ on GitHub and sharing it with your peers.  

Your support encourages more open-source contributions and helps grow the ML community! 🚀
