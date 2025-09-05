# 🏡 K-Nearest Neighbors (KNN) Regression for House Price Prediction using Scikit-learn

This project demonstrates how to implement a **K-Nearest Neighbors (KNN) Regression** model using the **Scikit-learn** library to predict **house prices** based on real-world style features such as square footage, number of bedrooms, bathrooms, and location scores. It highlights the effectiveness of KNN in regression problems where prediction accuracy depends on the similarity between data points.

---

## 📘 Project Overview

*K-Nearest Neighbors* is a non-parametric supervised learning algorithm that can be applied to both classification and regression tasks. In this notebook, we implement the **full regression pipeline** using Scikit-learn, covering:

- 📥 Load and inspect the housing dataset  
- 📊 Perform Exploratory Data Analysis (EDA) using **Seaborn** and **Matplotlib**  
- 🔍 Visualize correlations with a heatmap and scatter plots  
- ✂ Split the dataset using `train_test_split()`  
- 🔧 Preprocess features using **StandardScaler()**  
- 🧠 Train the model using `KNeighborsRegressor()`  
- 📈 Evaluate model performance using regression metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score  
- 📉 Visualize **Actual vs Predicted Prices** for performance validation  

---

## 📊 About the Dataset

The dataset contains **synthetic real-estate style data** simulating house sales, designed for regression tasks. Key columns include:

- 📏 *Square_Footage* — Total size of the property in square feet  
- 🛏 *Bedrooms* — Number of bedrooms in the house  
- 🛁 *Bathrooms* — Number of bathrooms in the house  
- 🏙 *Neighborhood_Score* — Location desirability rating (higher = better)  
- 💰 *Price* — Target variable representing the property’s selling price  

This dataset is ideal for demonstrating **supervised regression** and similarity-based learning methods like KNN.

---

## ✅ Features Implemented

- Data loading and initial inspection  
- Missing value checks and cleaning  
- Exploratory data analysis with Seaborn visualizations  
- Correlation analysis (heatmap + scatter plots)  
- Feature scaling using **StandardScaler()**  
- Model training with `KNeighborsRegressor()`  
- Performance evaluation with MAE, MSE, RMSE, R² Score  
- Actual vs Predicted price visualization  

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

- 📚 Learning how to implement KNN regression for continuous value prediction  
- 🏠 Real-estate price prediction models  
- 🧠 Practicing scaling, similarity-based modeling, and model evaluation in regression tasks  
- 📊 Understanding how to interpret evaluation metrics for regression performance  

---

## 👨‍💻 Author

*Zohaib Sattar*  
📧 Email: [zabizubi86@gmail.com](mailto:zabizubi86@gmail.com)  
🔗 LinkedIn: [Zohaib Sattar](https://www.linkedin.com/in/zohaib-sattar)

---

## ⭐ Support the Project

If this project helped you understand **KNN Regression** or enhanced your machine learning skills, please consider giving it a ⭐ on GitHub and sharing it with your network. Your support motivates me to build more open-source ML projects for the community! 🚀
