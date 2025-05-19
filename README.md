# 🚗 Auto Price Prediction Model

A machine learning project to predict car prices based on various technical and design features using multiple regression models. The project includes data cleaning, preprocessing, exploratory analysis, feature engineering, model comparison, and business insights.

---

## 🎯 Objective

To build a predictive model that helps understand how car prices vary with independent variables such as engine size, body style, fuel system, and more. The model supports management decisions on design, pricing strategy, and feature prioritization.

---

## 📊 Dataset

- **Source**: UCI Machine Learning Repository  
- **Format**: CSV with 205 rows and 26 features  
- **Target Variable**: `price`

---

## 🧪 Techniques Used

- Exploratory Data Analysis (EDA)
- Handling missing values and outliers
- Feature scaling with MinMaxScaler
- Encoding categorical variables
- Multicollinearity analysis and reduction
- Model training and comparison

---

## 🤖 Models Compared

| Model               | R² Score | RMSE  |
|---------------------|----------|-------|
| XGBoost Regressor   | 0.85     | 0.14  |
| Random Forest       | 0.84     | 0.15  |
| Linear Regression   | 0.72     | 0.19  |
| Ridge Regression    | 0.71     | 0.20  |
| Lasso Regression    | 0.18     | 0.33  |

✅ **XGBoost Regressor** was the best-performing model.

---

## 📈 Business Impact

- Identifies which car features have the most influence on price
- Helps management adjust design and features to meet target price levels
- Supports data-driven product positioning and marketing

---

## 📌 Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost


