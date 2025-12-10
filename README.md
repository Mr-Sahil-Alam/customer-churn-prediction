# Customer Churn Prediction (Python, Pandas, Scikit-learn)

This project predicts customer churn using telecom customer data. The goal is to identify customers at high risk of leaving so businesses can take early retention actions.

## 🔍 Project Highlights
- Performed data cleaning and preprocessing on 7,000+ customer records  
- Used One-Hot Encoding, StandardScaler, and SMOTE for feature engineering and imbalance handling  
- Trained and optimized a Random Forest classifier using GridSearchCV (ROC-AUC scoring)  
- Evaluated model using AUC, ROC curve, and confusion matrix  
- Analyzed feature importance to identify key churn drivers  
- Saved final model as a reproducible `.pkl` pipeline  

---

## 🧠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- Matplotlib  
- Jupyter Notebook  

---

## 📁 Project Structure
customer-churn-prediction/
│
├── notebooks/
│ └── Customer_Churn_Prediction.ipynb
│
├── models/
│ └── churn_pipeline_smote_rf.pkl
│
├── images/
│ ├── roc_curve.png
│ ├── confusion_matrix.png
│ └── feature_importance.png
│
├── requirements.txt
└── README.md


---

## 📊 Model Performance
- **Metric:** ROC-AUC (suited for imbalanced datasets)  
- **AUC Score:** Obtained using `predict_proba` for accurate churn ranking  
- Includes:
  - ROC Curve  
  - Confusion Matrix  
  - Feature Importance Visualization  

---

## 🔑 Key Insights
- Customers with short tenure churn more frequently  
- Month-to-month contract users have the highest churn risk  
- Higher monthly charges increase churn probability  
- Auto-pay and long-term contracts reduce churn  

---

## 🚀 How to Run Project
1. Clone the repository:




*
*
*

## 🙌 Author
**Sahil Alam**  
- LinkedIn: https://linkedin.com/in/sahilalam  
- GitHub: https://github.com/Mr-Sahil-Alam  
