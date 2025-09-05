# 🏥 ElasticNet Regression for Hospital Cost Prediction using Scikit-learn

This project demonstrates how to implement an *ElasticNet Regression* model using the *Scikit-learn* library to predict hospital charges based on patient demographic and health attributes. It highlights the effectiveness of ElasticNet in solving real-world regression problems with multicollinearity and high-dimensional features.

---

## 📘 Project Overview

*ElasticNet Regression* is a regularized linear regression model that combines both L1 (Lasso) and L2 (Ridge) penalties. In this notebook, we implement the full machine learning pipeline for regression using Scikit-learn, covering:

- 📥 Load and inspect the hospital dataset  
- 📊 Perform Exploratory Data Analysis (EDA) using Seaborn and Matplotlib  
- ✂ Split the dataset using `train_test_split()`  
- 🔧 Preprocess features using encoding and `StandardScaler()`  
- 🧠 Train a model using `ElasticNet()`  
- 🔍 Evaluate the model performance with regression metrics  
- 📈 Visualize actual vs predicted charges using scatter plots  

---

## 📊 About the Dataset

The dataset contains anonymized patient data with medical and demographic attributes. It is structured for regression tasks and includes the following columns:

- 👴 *Age* — Age of the patient  
- ⚧️ *Sex* — Gender of the patient  
- 🧮 *BMI* — Body Mass Index  
- 👶 *Children* — Number of children  
- 🚬 *Smoker* — Smoking status (yes/no)  
- 🌍 *Region* — Geographic region of the patient  
- 💰 *Charges* — Total medical cost billed (target variable)  

This dataset is ideal for applying regression models in health analytics, insurance pricing, and patient cost estimation.

---

## ✅ Features Implemented

- Data loading and initial inspection  
- Null value checks and data cleaning  
- Categorical encoding using `LabelEncoder()`  
- Feature scaling using `StandardScaler()`  
- Exploratory data analysis with visualizations  
- Model training using `ElasticNet()` from Scikit-learn  
- Model evaluation using:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)  
- Prediction visualization: actual vs predicted cost plot  

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

- 📚 Learning how to apply ElasticNet for regression problems  
- 💼 Predictive analytics in the healthcare and insurance domain  
- 🧠 Understanding regularization techniques for multicollinearity  
- 🧳 Adding a practical ML regression project to your data science portfolio  

---

## 👨‍💻 Author

*Zohaib Sattar*  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)

---

## ⭐ Support the Project

If this project helped you understand ElasticNet Regression or enhanced your ML skills, please consider giving it a ⭐ on GitHub and sharing it with your peers. Your support fuels future open-source contributions and keeps the data science community growing! 🚀
