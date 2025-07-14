# 📍 Waze User Churn Prediction – End-of-Course Machine Learning Project

## 🚀 Project Overview
This project builds machine learning models to **predict user churn** for Waze.  
By identifying key factors that lead users to stop using the app, the models help Waze take proactive steps to improve **user retention** and **grow its business**.

The work includes:
- Ethical considerations of predictive modeling
- Data exploration and feature engineering
- Building and evaluating two tree-based models: **Random Forest** and **XGBoost**

---

## 📊 Dataset
The dataset was provided as part of **Coursera's Google Advanced Data Analytics course**.  
It contains simulated Waze user activity and engagement data, including:
- User demographics
- App usage frequency and patterns
- Session activity
- Engagement features and feedback data

Target variable:
- **Churn status** — binary indicator showing whether a user churned (stopped using the app) or was retained.

---

## 🎯 Project Goals
- Predict whether a user will **churn** or be **retained**
- Identify the most influential features driving churn
- Help leadership make data-driven decisions to reduce churn

---

## 📈 Key Steps

### ✅ 1. Ethical Considerations
- Assessed impact of false positives and false negatives:
  - *False negative*: missing a churning user → missed retention opportunity
  - *False positive*: wrongly flagging a loyal user → potential annoyance
- Determined the benefits of prediction outweigh risks if strategies are thoughtfully applied.

### 🔧 2. Feature Engineering
- Selected, transformed, and created new features to improve model performance.
- Explored correlations and visualized distributions to better understand user behavior.

### 🌲 3. Modeling
- Built and tuned:
  - Random Forest Classifier
  - XGBoost Classifier
- Evaluated models using accuracy, precision, recall, and ROC-AUC.
- Analyzed **feature importance** to identify top drivers of churn.

---

## ⚙️ Technologies & Libraries
- Python (pandas, numpy, matplotlib)
- scikit-learn
- XGBoost

---

## 📌 Results & Impact
- Accurately predicted churn risk using tree-based models.
- Identified the most influential features affecting churn.
- Provided actionable insights to help Waze improve user retention.

---

## 🧭 Framework: PACE
This project follows the **PACE** problem-solving framework:
- **Plan**: Define objectives & assess ethical considerations
- **Analyze**: Explore and prepare data
- **Construct**: Build and evaluate models
- **Execute**: Summarize findings & recommend next steps

![Confusion matrix] (https://github.com/Garnix123/waze_customer_churn_machine_learning_model/blob/4acfc8d69223a5ced534bf630c98b1ff386cd022/Screenshot%202025-07-14%20at%2015.30.31.png)
