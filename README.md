# 📸 Instagram Engagement Prediction – Regression Model Comparison

This project aims to predict the number of likes on Instagram posts using various regression techniques. It compares the performance of **Linear Regression**, **Ridge**, **Lasso**, **RANSAC**, and **Huber Regression** to understand their behavior on social media engagement data, particularly in the presence of outliers.

---

## 🧠 Objective

To explore and compare the effectiveness of different regression models for predicting Instagram post likes and assess how robust each model is to outliers or noise in the dataset.

---

## 🧪 Models Used

- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Huber Regressor** (Robust to outliers)
- **RANSAC Regressor** (Robust model fitting with inlier detection)

---

## 📈 Workflow

1. **Data Cleaning** – Handled missing values and formatted data
2. **Feature Scaling** – Applied normalization to ensure fair model comparison
3. **Model Training** – Trained 5 different regressors on the dataset
4. **Evaluation Metrics** – Used MAE, MSE, R², and visual error comparison
5. **Outlier Analysis** – Observed how each model handles noisy data

---

## 🔧 Tools & Libraries

- **Python**
- `scikit-learn`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`

---

## 📊 Key Insights

- **Linear Regression** performed well under normal data but was sensitive to outliers.
- **Huber Regression** offered a balanced performance by reducing outlier impact.
- **RANSAC** was best for noisy data but less stable when too many inliers were removed.
- **Ridge and Lasso** showed improved generalization through regularization but varied with alpha values.

> **Huber Regressor** was found to be the most suitable for this dataset due to its resilience against outliers.




