# 🏠 House Price Prediction using Regression

This project is part of my learning journey through [Andrew Ng's Machine Learning Course](https://www.coursera.org/learn/machine-learning). After learning the theory behind regression, I wanted to apply it practically using both simple and advanced models to deepen my understanding.

---

## 📌 About the Project

This notebook builds models using the **Boston Housing Dataset** to predict housing prices based on 13 features such as crime rate, number of rooms, pupil-teacher ratio, and more.

To learn effectively, I experimented with:
- **XGBRegressor**: A powerful, optimized gradient boosting algorithm
- **SGDRegressor**: A linear model optimized using stochastic gradient descent

---

## 🎯 Objective

- Apply concepts from Andrew Ng’s ML course in real-world data
- Learn and compare traditional and modern regression models
- Evaluate performance using industry-standard metrics
- Visualize predictions to understand model behavior

---

## 📊 Dataset

- **Source:** Boston Housing dataset (from Kaggle)
- **Input Features:** 13 (e.g., `CRIM`, `RM`, `LSTAT`)
- **Target:** `MEDV` — Median value of owner-occupied homes (in $1000s)

---

## 🛠 Libraries Used

| Library        | Purpose |
|----------------|---------|
| **NumPy**      | Numerical computations, array math |
| **Pandas**     | Data handling and preprocessing |
| **Matplotlib** | Creating plots (prediction vs target) |
| **Seaborn**    | Correlation heatmaps and visual insights |
| **Scikit-learn** | Train-test split, model evaluation (MAE, R²), and **SGDRegressor** for linear regression using gradient descent |
| **XGBoost (`xgboost`)** | Used `XGBRegressor` — a powerful ensemble learning algorithm based on gradient boosting |
| **IPython.display** | (Optional) For linking downloads inside notebook interface |

---

## 🤖 Models Used

| Model           | Description |
|-----------------|-------------|
| **SGDRegressor** | Linear regression using **Stochastic Gradient Descent** — fast and scalable for large datasets |
| **XGBRegressor** | An advanced **gradient boosting model** — handles feature interactions better and usually performs better out-of-the-box |

Both models were compared using:
- **Mean Absolute Error (MAE)**
- **R² Score**

---

## 🖼 Visualizations

- Feature-target scatter plots
- Prediction vs actual plots for all 14 features
- Correlation heatmap to identify important features

---

## 📎 Files Included

- `house-price-prediction-model-using-regression.ipynb` — Main notebook with both models, visualizations, and evaluation

---

