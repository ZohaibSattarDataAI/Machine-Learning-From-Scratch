# 📊 Principal Component Regression (PCR)

## 📌 Definition
Principal Component Regression (PCR) is a regression technique that combines **Principal Component Analysis (PCA)** with **Linear Regression**.  
It reduces the dimensionality of the dataset by transforming correlated predictors into a set of linearly uncorrelated variables called **principal components**, and then applies regression on these components.

---

## 📖 Description
- PCR is especially useful when the dataset has **multicollinearity** (when predictors are highly correlated).  
- Instead of using the original correlated variables, PCR uses the **principal components** (PCs), which are linear combinations of the original variables.  
- The first few PCs usually explain most of the variance in the data, and regression is performed using only these components.  
- This reduces **overfitting** and improves **model stability**.

---

## 🎯 Applications
PCR is widely used in fields where datasets are **high-dimensional** or where predictors are **correlated**:
1. **Chemometrics** – analyzing chemical and spectral data.  
2. **Genomics & Bioinformatics** – analyzing gene expression data.  
3. **Economics & Finance** – forecasting with correlated economic indicators.  
4. **Image Processing** – dimensionality reduction in image recognition tasks.  
5. **Environmental Science** – climate and pollution modeling.  

---

## 🔧 Usage
- When predictors are highly correlated (multicollinearity problem).  
- When the dataset has **more predictors than observations**.  
- When dimensionality reduction is required before regression.  
- When interpretability of predictors is less important than predictive accuracy.  

---

## ✅ Pros
- Handles **multicollinearity** effectively.  
- Reduces **dimensionality**, making the model simpler.  
- Improves **model stability** and avoids overfitting.  
- Can work with **high-dimensional data** (p >> n).  
- Enhances predictive performance when irrelevant/noisy features exist.  

---

## ❌ Cons
- Principal components are **linear combinations** of features, so they lose **direct interpretability**.  
- PCR selects components based on **variance explained**, not on their **predictive power**.  
- Risk of **underfitting** if too few components are selected.  
- Requires extra step of determining the optimal number of PCs.  
- Not always the best when prediction is the only goal — methods like **PLS (Partial Least Squares)** may outperform PCR.  

---

## 📌 Summary
Principal Component Regression (PCR) is a powerful technique for regression analysis when dealing with **high-dimensional** or **multicollinear datasets**.  
It simplifies the data using PCA, then applies regression on the most informative components. While it improves **model robustness** and **reduces noise**, it sacrifices some interpretability of the predictors.

