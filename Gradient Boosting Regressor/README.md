# 🔟 Gradient Boosting Regressor for Financial Risk Prediction using Scikit-learn

This is my **tenth machine learning project**, where I implemented a powerful **Gradient Boosting Regressor** using the Scikit-learn library to predict financial risk based on structured user-level transaction data. This project highlights the effectiveness of ensemble learning techniques in regression tasks, especially for complex financial datasets.

---

## 📘 Project Overview

*Gradient Boosting Regressor (GBR)* is an advanced ensemble model that builds multiple decision trees in a sequential manner to minimize error. This project follows a complete end-to-end pipeline for training and evaluating GBR on a financial dataset, including:

- 📥 Data loading and exploration
- 📊 Exploratory Data Analysis (EDA) using Matplotlib and Seaborn
- ✂ Data splitting with `train_test_split()`
- 🔧 Feature scaling using `StandardScaler()`
- 🌳 Model training using `GradientBoostingRegressor()`
- 🔍 Model tuning with hyperparameters like `max_depth`, `n_estimators`, etc.
- 📈 Evaluation using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- 🧮 Visualization of predictions vs actual values

---

## 📊 About the Dataset

This dataset simulates financial behavior and is designed for regression-based prediction of risk-related scores. It contains the following features:

- 👴 `age` — Age of the customer
- 📆 `account_age_months` — Duration of account activity
- 💳 `num_transactions` — Number of transactions performed
- 💰 `avg_transaction_value` — Average transaction size
- 🧠 `credit_score` — Existing credit rating
- 💸 `income` — Annual income of the individual
- 🕒 `days_since_last_transaction` — Activity recency
- 💵 `transaction_amount` — Amount in latest transaction
- 🎯 `Prediction` — Target variable for financial risk

---

## ✅ Features Implemented

- Cleaned and preprocessed data
- Feature scaling using StandardScaler
- Gradient Boosting model implementation
- Manual parameter tuning
- Visual and statistical evaluation of model performance
- Achieved strong R² and low error metrics

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

- 📉 Financial risk scoring for banking or fintech
- 📈 Predicting creditworthiness based on transactions
- 🧠 Ensemble model application in real-world datasets
- 📚 Regression practice for portfolio and interviews

---

## 👨‍💻 Author

**Zohaib Sattar**  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)

---

## ⭐ Support the Project

If you found this project useful for learning or developing regression skills using ensemble models, consider giving it a ⭐ on GitHub and sharing it with your connections. Your support motivates further open-source contributions! 🚀

