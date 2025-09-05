# ⚡ AdaBoost (Adaptive Boosting)

---

## 📖 Definition
**AdaBoost (Adaptive Boosting)** is an ensemble machine learning algorithm that combines multiple weak learners, typically shallow decision trees, to form a strong predictive model. It works by assigning weights to misclassified observations and iteratively improving performance by focusing on the harder-to-predict samples.

---

## 📝 Description
AdaBoost was one of the first boosting algorithms introduced and remains a popular choice for classification and regression tasks.  
The key idea is to **boost weak learners** by training them sequentially, where each new model corrects the mistakes of the previous one. The final prediction is made by combining all learners with weighted contributions based on their accuracy.

- In **classification**, AdaBoost adjusts the weights of misclassified samples.  
- In **regression**, it reduces error by combining multiple weak regressors to minimize the overall prediction loss.  

---

## ⚙️ Usage
AdaBoost is widely used for:
- Improving prediction accuracy on structured/tabular data.  
- Handling both classification and regression problems.  
- Situations where interpretability and simplicity are important.  
- Acting as a strong baseline before trying more complex models like Gradient Boosting or XGBoost.  


