# Concrete Compressive Strength Prediction

## 📌 Overview
This project predicts the **compressive strength of concrete** using its material composition and curing age.
A regression-based machine learning approach is applied to understand how different ingredients influence concrete strength.

---

## 🎯 Problem Statement
Concrete strength is affected by multiple factors such as cement quantity, water content, aggregates, and age.
The objective of this project is to build a regression model that accurately predicts **concrete compressive strength**
using these input features.

---

## 📊 Dataset Description
The dataset contains **numerical features** related to concrete composition.

### Input Features
- `cement` – Cement content
- `slag` – Blast furnace slag
- `ash` – Fly ash
- `water` – Water content
- `superplastic` – Superplasticizer
- `coarseagg` – Coarse aggregate
- `fineagg` – Fine aggregate
- `age` – Age of concrete (in days)

### Target Variable
- `strength` – Concrete compressive strength

---

## 🛠️ Methodology
1. Data loading and inspection
2. Checking missing values and data types
3. Exploratory Data Analysis (EDA)
4. Feature and target separation
5. Train-test split
6. Regression model training
7. Model evaluation

---

## 🤖 Models Used
- Linear Regression
- Ridge Regression
- Lasso Regression

---

## 📈 Evaluation Metrics
- R² Score
- Mean Squared Error (MSE)

---

## 🔍 Key Insights
- Cement content and age have strong influence on strength
- Regularization improves model generalization
- Linear models provide a strong baseline for this dataset

---

## 🚀 Future Enhancements
- Use ensemble regression models
- Hyperparameter tuning
- Feature importance visualization
- Model deployment using Streamlit

---

## 🧠 Learnings
- Regression modeling on real-world data
- Understanding feature relationships
- Model evaluation and comparison
