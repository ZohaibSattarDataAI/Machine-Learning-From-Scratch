# 🔟 Tweedie Regressor for Drug Effectiveness Prediction using Scikit-learn  

This is my **thirteenth machine learning project**, where I implemented a **Tweedie Regressor** using the Scikit-learn library to predict treatment effectiveness scores.  
This project highlights the flexibility of the **Tweedie family of models** in handling diverse data distributions, ranging from **Normal** and **Poisson** to **compound Poisson-Gamma** cases.  

---

## 📘 Project Overview  
Tweedie Regressor is a **Generalized Linear Model (GLM)** that unifies multiple probability distributions by adjusting its `power` parameter.  
This project follows a complete end-to-end pipeline for training and evaluating Tweedie Regression on structured medical data, including:  

- 📥 Data loading and preprocessing  
- 📊 Exploratory Data Analysis (EDA) using Matplotlib  
- ✂ Data splitting with `train_test_split()`  
- 🔧 Feature scaling using `StandardScaler()`  
- 📈 Model training using `TweedieRegressor()`  
- 🔍 Model evaluation with regression metrics  
- 🧮 Visualization of predictions vs actual values  

---

## 📊 About the Dataset  
The dataset contains structured medical-related features used for predicting drug effectiveness:  

- **Drug_Class** → Category of the drug administered  
- **Dosage** → Prescribed dosage of the drug  
- **Age** → Age of the patient  
- **Duration** → Treatment duration  
- **Effectiveness_Score** → Measured effectiveness of the treatment  
- **Prediction** → Target variable predicted by the model  

---

## 🎯 Model Performance  
- 📉 **MAE:** 2.46  
- 📉 **MSE:** 10.14  
- 📉 **RMSE:** 3.18  
- 🎯 **R² Score:** 95.84%  

---

## ✅ Features Implemented  
- Cleaned and preprocessed data  
- Feature scaling using `StandardScaler`  
- Tweedie Regression model implementation  
- Performance evaluation with **MAE, MSE, RMSE, and R²**  
- Visual and statistical evaluation of predictions  
- Achieved **strong R² with low error metrics**  

---

## 🧪 Technologies Used  
- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📂 Use Cases  
- 📊 Predicting drug effectiveness in healthcare datasets  
- 🧮 Generalized linear modeling for **medical, insurance, and finance domains**  
- 📚 Regression modeling practice for **portfolios and technical interviews**  

---

## 👨‍💻 Author  
**Zohaib Sattar**  
- 📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
- 🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)  

---

## ⭐ Support the Project  
If you found this project useful for learning or practicing regression modeling, consider giving it a ⭐ on GitHub and sharing it with your network.  
Your support motivates further **open-source contributions! 🚀**  
