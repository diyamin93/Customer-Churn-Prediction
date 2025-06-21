Context
"Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs." [IBM Sample Data Sets]

Content
Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

The data set includes information about:

Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents.

# Customer Churn Prediction 📉

This project predicts customer churn using the IBM Telco Customer Churn dataset. The goal is to help businesses identify customers likely to leave and improve retention strategies.

## 🧠 Models Used
- Random Forest
- XGBoost

## 🔧 Techniques
- Data Preprocessing
- Label Encoding
- SMOTE (for class imbalance)
- GridSearchCV (for hyperparameter tuning)
- Evaluation with accuracy, confusion matrix, ROC-AUC

## 📁 Files
- `Customer Churn Prediction.ipynb`: Full notebook with model training and evaluation
- `app.py`: Python script to serve the model (Flask/FastAPI)
- `templates/index.html`: Basic front-end for interaction
- `fastapi_app.py`: REST API using FastAPI

## 🚀 How to Run

```bash
pip install -r requirements.txt
python app.py
