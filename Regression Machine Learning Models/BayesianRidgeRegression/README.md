# 🧮 Bayesian Ridge Regression for Sales Revenue Prediction using Scikit-learn

This project demonstrates how to implement a **Bayesian Ridge Regression** model using the **Scikit-learn** library to predict sales revenue based on various marketing and seasonal features. Bayesian Ridge is especially useful for regression problems where **multicollinearity** may exist or when we want to introduce **probabilistic reasoning** into our models.

---

## 📘 Project Overview

**Bayesian Ridge Regression** is a linear model that applies regularization through Bayesian inference. It assumes the weights of the regression model are drawn from a Gaussian distribution, and it estimates both the weights and the noise of the model from the data itself. This allows for **robust, stable predictions**, especially when features are **correlated**.

> 🧠 **When to Use It:**  
Bayesian Ridge Regression is particularly effective when working with:
- **Small to medium-sized datasets**
- **High-dimensional or multicollinear features**
- **Need for regularized and probabilistic outputs**
- Use cases in **finance**, **medical forecasting**, **sales prediction**, and **scientific research**, where uncertainty estimation adds value.

### The pipeline includes:

- 📥 Loading a marketing dataset  
- 📊 Performing exploratory data analysis (EDA) using Seaborn and Matplotlib  
- ✂ Splitting the dataset using `train_test_split()`  
- 🔧 Scaling features using `StandardScaler()`  
- 🧠 Training a Bayesian Ridge model using `BayesianRidge()`  
- 📈 Evaluating model performance with:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)  
- 📉 Visualizing actual vs predicted sales revenue

---

## 📊 About the Dataset

This is a **synthetic marketing dataset** designed to simulate real-world ad performance and seasonality impact on sales revenue. The dataset includes the following features:

- 📺 `ad_spend_tv` — TV advertisement spend  
- 📻 `ad_spend_radio` — Radio advertisement spend  
- 📱 `ad_spend_social` — Social media ad spend  
- 🌐 `website_visits` — Number of website visits  
- ✉️ `email_campaigns_sent` — Number of marketing emails sent  
- 🍂 `season_autumn`, 🌸 `season_spring`, ☀️ `season_summer`, ❄️ `season_winter` — Season indicators (dummy variables)  
- 💰 `sales_revenue` — Target variable (total sales revenue)  
- 📈 `Prediction` — Model-generated sales revenue prediction

---

## ✅ Features Implemented

- Cleaned and preprocessed marketing data  
- Created seasonal dummy variables  
- Applied Bayesian Ridge Regression  
- Scaled features to standard distribution  
- Evaluated model accuracy using R², MAE, and MSE  
- Visualized actual vs predicted sales using scatter and line plots  

---

## 🧪 Technologies Used

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📂 Use Cases

This notebook is ideal for:

- 📚 Learning to apply **Bayesian regression** for real-world datasets  
- 📊 Predicting revenue based on marketing KPIs  
- 🧠 Improving performance where **Linear Regression fails** due to multicollinearity  
- 🧳 Building interpretable, probabilistic machine learning models for portfolios or clients  

---

## ✅ Conclusion

- **Bayesian Ridge Regression** achieved an R² score of **95%+**, showing excellent prediction accuracy.
- The model performed well in the presence of multiple correlated marketing features.
- Bayesian modeling enabled **probabilistic predictions**, making it well-suited for **forecasting in uncertain environments**.
- This project confirms that Bayesian Ridge is a reliable method when regularization and uncertainty estimation are critical.

---

## 👨‍💻 Author

**Zohaib Sattar**  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)

---

## ⭐ Support the Project

If you found this project helpful or insightful, please consider giving it a ⭐ on GitHub. It motivates me to keep creating valuable open-source data science content and helps others discover this work. Thank you for your support! 🚀
