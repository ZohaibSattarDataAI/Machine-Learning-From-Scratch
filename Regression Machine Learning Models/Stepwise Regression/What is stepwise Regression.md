# 📊 Stepwise Regression (Forward & Backward)

Stepwise regression is a **variable selection method** used in regression modeling. It helps in **identifying the most significant predictors** from a large set of variables by adding or removing features step by step.  
The primary goal is to build a model that is **both accurate and simple**, avoiding overfitting and improving interpretability.  

---

## 🔹 Types of Stepwise Regression  

### 1. **Forward Stepwise Regression**
- Starts with **no predictors** in the model.  
- Adds predictors **one at a time**, selecting the one that improves the model the most (based on criteria such as **R², AIC, BIC, or p-value**).  
- The process continues until **no further significant improvement** is achieved.  

✅ **Steps:**  
1. Start with an empty model.  
2. Add the variable that improves model performance the most.  
3. Repeat until no significant improvement is possible.  

---

### 2. **Backward Stepwise Regression**
- Starts with **all predictors** included.  
- Removes the **least significant predictor** one at a time.  
- Stops when all remaining predictors are significant and improve the model.  

✅ **Steps:**  
1. Start with all variables in the model.  
2. Remove the variable with the **least contribution**.  
3. Repeat until only significant predictors remain.  

---

## 🛠️ Applications of Stepwise Regression  
Stepwise regression is commonly used in:  
- **Machine Learning & AI** → Feature selection before model building.  
- **Economics & Finance** → Identifying key economic indicators affecting growth or stock performance.  
- **Medical Research** → Selecting significant risk factors for diseases.  
- **Marketing Analytics** → Choosing important features impacting sales or customer behavior.  
- **Engineering & Science** → Simplifying models by selecting only impactful variables.  

---

## ⚡ Advantages  
- Reduces the **risk of overfitting** by removing irrelevant predictors.  
- Improves **model interpretability** by keeping only important features.  
- Helps in **automatic feature selection** without manual trial and error.  
- Saves computational resources when dealing with large datasets.  

---

## ⚠️ Limitations  
- Can sometimes exclude variables that are **important in combination** with others.  
- May lead to **unstable models** (small changes in data can change selected features).  
- Not suitable when predictors are **highly correlated** (multicollinearity).  
- Relies heavily on the **chosen evaluation metric** (e.g., R², AIC).  

---

## 🚀 Usage in Python (Scikit-learn + mlxtend)  

```python
from sklearn.linear_model import LinearRegression
from mlxtend.feature_selection import SequentialFeatureSelector as SFS

# Model
lr = LinearRegression()

# Forward Stepwise Regression
sfs = SFS(lr,
          k_features="best",
          forward=True,     # Forward Selection
          floating=False,
          scoring="r2",
          cv=5)

sfs = sfs.fit(X_train, y_train)
print("Selected Features (Forward):", sfs.k_feature_names_)

# Backward Stepwise Regression
sbs = SFS(lr,
          k_features="best",
          forward=False,    # Backward Selection
          floating=False,
          scoring="r2",
          cv=5)

sbs = sbs.fit(X_train, y_train)
print("Selected Features (Backward):", sbs.k_feature_names_)
```
## 📌 Conclusion

**Stepwise regression** is a powerful feature selection technique that balances model performance and simplicity.

**Forward Selection** → Best when starting with no prior knowledge of features.

**Backward Selection** → Best when starting with many features and filtering out irrelevant ones.

Although it has limitations (like instability and multicollinearity issues), stepwise regression remains a valuable tool in predictive modeling, statistics, and machine learning.

