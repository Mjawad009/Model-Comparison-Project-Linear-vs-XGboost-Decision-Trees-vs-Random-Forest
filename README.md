# 🏡 Random Forests vs XGBoost: California Housing Price Prediction

This project compares the performance of two popular ensemble machine learning algorithms — **Random Forest Regressor** and **XGBoost Regressor** — on the **California Housing dataset**. The goal is to evaluate accuracy, training time, and generalization ability for predicting median house prices.

---

## 📌 Project Objectives

- Load and explore the California Housing dataset
- Train two regression models:
  - `RandomForestRegressor`
  - `XGBRegressor`
- Compare:
  - Model accuracy (R² score, RMSE)
  - Training times
  - Overfitting/underfitting behavior
    
  ## 🚀 Model Performance Comparison

| Model              | 🧠 Train Time | ⚡ Predict Time | 📉 MSE    | 📈 R² Score |
|--------------------|---------------|----------------|-----------|-------------|
| Linear Regression  | 0.007 s       | 0.004 s        | 0.5559    | 0.5758      |
| Decision Tree      | 0.301 s       | 0.003 s        | 0.4952    | 0.6221      |
| Random Forest      | 18.753 s      | 0.161 s        | 0.2554    | 0.8051      |
| XGBoost            | 0.426 s       | 0.009 s        | 0.2226    | 0.8301      |

---

### 🔍 Insights

- ✅ **XGBoost** leads in accuracy, achieving the **highest R² score** and **lowest MSE**.
- 🌲 **Random Forest** performs very well in accuracy but takes significantly longer to train.
- 🧮 **Linear Regression** and **Decision Tree** are fast and simple, but less accurate.
- ⚡ **XGBoost** hits the **sweet spot** between speed and accuracy—making it a **top choice for real-world applications**.

---

## 🧠 What You’ll Learn

- Core concepts of **Bias vs. Variance**
- How **ensemble methods** improve performance
- Practical difference between:
  - Bagging (`RandomForest`)
  - Boosting (`XGBoost`)
- Model evaluation using real-world data

---

## 📊 Dataset

- **Source**: California Housing dataset (`sklearn.datasets.fetch_california_housing`)
- **Target**: Median House Value (in $100,000s)
- **Features**: 8 numerical variables (e.g., Median Income, House Age, Rooms, Population)

---

## 🚀 Models Used

| Model                 | Ensemble Type | Method      | Strengths                     |
|----------------------|---------------|-------------|-------------------------------|
| Random Forest         | Bagging       | Parallel    | Reduces variance, robust      |
| XGBoost               | Boosting      | Sequential  | Reduces bias, high accuracy   |

---

## 🛠️ Tech Stack

- Python 3.x
- Jupyter Notebook
- Scikit-learn
- XGBoost
- NumPy, Matplotlib

---

## 📈 Evaluation Metrics

- **R² Score** – Coefficient of determination
- **RMSE** – Root Mean Squared Error
- **Training Time** – Time taken to fit each model

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/random-forest-vs-xgboost.git
   cd random-forest-vs-xgboost
