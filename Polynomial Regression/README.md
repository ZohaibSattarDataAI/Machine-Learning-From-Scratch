# 📈 Polynomial Regression using Scikit-learn

This project demonstrates how to implement **Polynomial Regression** in Python using **Scikit-learn**, applied to a dataset involving stock market features such as sentiment scores and volume. Polynomial regression is a powerful extension of linear models that captures non-linear relationships in data.

---

## 📘 Project Overview

Polynomial Regression allows us to model more complex patterns in data by introducing higher-degree terms of the input features. This project uses `PolynomialFeatures` with **degree=3** to predict stock prices based on multiple input variables.

### ✅ Key Highlights:
- Real-world multi-feature stock dataset
- Polynomial feature transformation
- Train-test split for evaluation
- Model training using `LinearRegression()`
- Performance metrics evaluation
- Visualization of actual vs predicted prices

---

## 📊 About the Dataset

The dataset used is a **multi-feature stock market dataset** containing columns such as:

- 🧠 `Sentiment_Score`: Sentiment analysis of stock-related text  
- 📈 `Volume`: Stock trading volume  
- 🕒 `Age`: Possibly time-related or temporal indicator  
- 💰 `Close`: Target variable (stock closing price)

The goal is to use these features to accurately predict stock prices, even when the relationship is not strictly linear.

---

## 🧠 Algorithms and Techniques Used

- Polynomial Regression (degree 3)
- Feature Transformation with `PolynomialFeatures`
- Model Training using Scikit-learn's `LinearRegression`
- Train/Test Data Split
- Error Metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Data visualization with `Seaborn` and `Matplotlib`

---

## 🛠️ Installation

To run the notebook, install the following libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```


---

## 🎯 Use Cases

- 📚 Educational use for learning regression
- 🧠 Practice project for ML beginners
- 🎓 Final year ML assignments
- 📁 Portfolio project for job interviews

---

## 👨‍💻 Author

**Zohaib Sattar**  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)

---

## ⭐️ Support the Project

If this project helped you learn or saved your time, please ⭐️ star the repo and share it. It keeps the motivation high for open-source contributors!
