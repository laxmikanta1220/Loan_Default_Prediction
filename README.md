# 💳 Loan Default Prediction & Recommendation System

## 📌 Project Overview

This project builds an end-to-end Machine Learning system to predict whether a loan applicant is likely to default or not.

It uses advanced ML techniques like **XGBoost**, **data pipelines**, and **Explainable AI (SHAP)** to not only predict risk but also provide actionable recommendations.

---

## 🚀 Key Features

* 📊 Exploratory Data Analysis (EDA)
* 🔄 Data Preprocessing using Pipeline & ColumnTransformer
* ⚡ Boosting Model (XGBoost)
* 📈 Model Evaluation (ROC-AUC, Precision, Recall, F1-score)
* 🧠 Explainable AI using SHAP
* 💡 Rule-based Recommendation System

---

## 📂 Dataset

* Source: Kaggle Loan Default Dataset
* Contains customer financial and demographic details
* Target variable: Loan Default (0 = No, 1 = Yes)

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn
* SHAP

---

## ⚙️ Project Workflow

1. **Data Loading**
2. **EDA (Exploratory Data Analysis)**
3. **Data Cleaning & Preprocessing**

   * Handling missing values
   * Encoding categorical variables
   * Feature scaling
4. **Pipeline Creation**

   * ColumnTransformer for preprocessing
5. **Model Training**

   * XGBoost Classifier
6. **Model Evaluation**

   * Confusion Matrix
   * ROC-AUC Curve
7. **Explainability**

   * SHAP feature importance
8. **Recommendation System**

   * Suggest actions for high-risk customers

---

## 📊 Model Performance

* ROC-AUC Score: XX.XX
* Precision: XX%
* Recall: XX%
* F1-score: XX%

---

## 💡 Business Impact

* Helps financial institutions reduce loan default risk
* Supports better decision-making in loan approvals
* Provides actionable insights for risk mitigation

---

## 🔍 Sample Prediction

**Input:**
Customer details

**Output:**

* Prediction: Default / No Default
* Recommendation:

  * Reduce loan amount
  * Increase repayment duration
  * Improve credit score

---

## ▶️ How to Run

```bash
# Clone repository
git clone https://github.com/your-username/loan-default-prediction.git

# Navigate to folder
cd loan-default-prediction

# Install dependencies
pip install -r requirements.txt

# Run project
python main.py
```

---

## 📁 Project Structure

```
├── data/
├── notebooks/
├── src/
├── models/
├── requirements.txt
├── README.md
```

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Handling class imbalance (SMOTE)
* Model deployment (Streamlit / Flask)
* Real-time prediction API

---

## 👨‍💻 Author

Laxmikanta Biswal
B.Tech CSE (AI & ML) Student

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!