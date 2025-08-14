# 🏠 Airbnb Price Prediction & Insights

## 📌 Overview
Airbnb is a global platform that allows property owners to rent out their spaces to travelers.  
Setting the **right price** for a listing is crucial for:
- Staying competitive
- Attracting bookings
- Maximizing revenue

This project focuses on building a **machine learning regression model** to predict the price of an Airbnb listing using features such as:
- Property type
- Room type
- Location
- Amenities
- Host characteristics

Alongside prediction, the project also delivers **data-driven insights** that hosts can use to optimize their pricing strategy.

---

## 🎯 Project Objective
Develop a **regression model** that predicts the nightly price of an Airbnb listing.  

The analysis aims to:
1. Identify the **key factors** that influence pricing.
2. Help hosts make **data-backed pricing decisions**.
3. Provide actionable insights for improving listing competitiveness.

---

## Dataset
- **Name:** `Airbnb_data`
- **Source:** [Download Airbnb_data.csv](https://docs.google.com/spreadsheets/d/1CGa4scSn_pLTr2e02UUJR5ffdhe85mix/edit?usp=sharing&ouid=104068375114358654660&rtpof=true&sd=true)


---

## 📦 Project Deliverables

### **1. Data Exploration & Preprocessing **
- Explored dataset for patterns and trends.
- Identified and handled missing values and outliers.
- Performed feature engineering (e.g., number of amenities, neighborhood popularity).
- Applied transformations for model readiness.

### **2. Model Development **
- Trained and evaluated multiple regression algorithms:
  - Linear Regression
  - KNN Regression
  - Support Vector Machine(SVM)
  - Decision Tree Regressor
  - Random Forest Regressor
  - XGBoost Regressor
- Compared models on **RMSE**, **MAE**, and **R²** scores.
- Selected the best-performing model for deployment.

### **3. Model Evaluation **
- Evaluated models on test set using:
  - RMSE (Root Mean Square Error)
  - MAE (Mean Absolute Error)
  - R² (Coefficient of Determination)
- Ensured selected model had a good balance between accuracy and generalization.

- **Model Comparison Table:**


| Algorithm               | R²     | RMSE   | MAE   |
|------------------------|--------|--------|-------|
| **XGBoost (Tuned)**    | 0.717  | 0.381  | 0.276 |
| Random Forest          | 0.699  | 0.393  | 0.283 |
| SVM Regressor          | 0.637  | 0.432  | 0.314 |
| Linear Regression      | 0.605  | 0.450  | 0.333 |
| KNN Regressor          | 0.557  | 0.477  | 0.352 |
| Decision Tree          | 0.402  | 0.554  | 0.397 |

---

## 📋 Project Guidelines
- **Data Splitting:** Train-validation-test split for robust evaluation.
- **Feature Engineering:** Create meaningful derived variables.
- **Hyperparameter Tuning:** Used GridSearchCV/RandomizedSearchCV for optimization.
- **Visualization:** Included charts to present trends and results.
- **Interpretability:** Ensured non-technical stakeholders can understand findings.

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Libraries:**
  - pandas, numpy → Data processing
  - matplotlib, seaborn → Visualization
  - scikit-learn → Modeling (Linear Regression, KNN, SVM, Decision Tree, Random Forest, Gradient Boosting)
  - XGBoost → Gradient boosting
- **Environment:** Jupyter Notebook
