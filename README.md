# Customer Churn Prediction

An end-to-end machine learning project for predicting customer churn using Logistic Regression and Scikit-learn pipelines.

## 📌 Project Overview

Customer churn prediction helps businesses identify customers who are likely to leave a service.  
This project focuses on building a clean and interpretable machine learning pipeline for churn prediction using structured customer data.

The workflow includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training
- Model evaluation

---

## 🧠 Models Tested

- Logistic Regression
- Random Forest
- XGBoost

After comparing multiple models, Logistic Regression was selected as the final model due to:
- good generalization
- interpretability
- stable performance
- conceptual simplicity

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## 🔄 ML Workflow

1. Data Cleaning
2. Handling Missing Values
3. Feature Encoding
4. Scaling Numerical Features
5. Pipeline Creation
6. Train-Test Split
7. Model Training
8. Performance Evaluation

---

## 📊 Final Logistic Regression Performance

| Metric | Score |
|---|---|
| Accuracy | 0.83 |
| F1 Score | 0.84 |
| Precision | 0.87 |
| Recall | 0.81 |

The model showed strong generalization, with nearly identical train and test accuracy scores.

---

## 📈 Key Learning Outcomes

During development, an initial issue was discovered where separate datasets caused distribution mismatch and unstable model performance.

This was resolved by:
- combining datasets
- using randomized train-test splitting
- implementing proper preprocessing pipelines

This project helped in understanding:
- overfitting
- data leakage
- preprocessing pipelines
- evaluation metrics
- model generalization

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Deployment using Flask/Streamlit
- Advanced feature engineering

---

## 📂 Repository Structure

```
customer-churn-prediction/
│
├── data/
├── notebooks/
├── churn_prediction.ipynb
├── requirements.txt
└── README.md
```

---

## 🤝 Author

Prathamesh More  
B.Tech AIML Student
