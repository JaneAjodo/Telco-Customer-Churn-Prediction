# 📈 Telco Customer Churn Prediction

This project uses machine learning to predict customer churn in the telecom industry. It is part of my portfolio for the IBM Data Science Professional Certificate.

## 🧠 Objective

To help telecom companies identify customers likely to churn and take proactive retention measures.

## 📊 Dataset

- Source: Kaggle – [Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- Features: Demographics, contract type, tenure, internet services, charges
- Target: `Churn` (Yes/No)

## 🔍 Process

1. **Data Cleaning**: Converted `TotalCharges`, dropped irrelevant columns, encoded `Churn`.
2. **EDA**: Identified churn patterns by contract, tenure, charges.
3. **Preprocessing**: One-hot encoding, feature scaling, train-test split.
4. **Handling Imbalance**: Applied SMOTE on training set.
5. **Modeling**:
   - Logistic Regression (ROC AUC: 0.83)
   - Random Forest Classifier
6. **Evaluation**: Confusion matrix, classification report, ROC AUC.

## 🧠 Key Insights

- Month-to-month contracts and high monthly charges are strong churn indicators.
- Early retention strategies should focus on new customers.

## 🛠️ Tools

- Python (Pandas, NumPy, Scikit-learn, Matplotlib)
- Jupyter Notebook

## 📁 Project Structure
telco-churn/
├── data/
├── notebooks/
├── models/
└── Customer Churn.ipynb

## 📌 Future Work

- Test XGBoost, LightGBM
- Cost-sensitive learning
- Real-time dashboard integration

---

### 🔗 [View Full Report](https://medium.com/@janeajodo/telco-customer-churn-prediction-480458c83399edit/main/README.md)


