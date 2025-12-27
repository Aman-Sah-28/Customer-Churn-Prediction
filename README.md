# Customer Churn Prediction

This project focuses on predicting whether a customer will leave (churn) a telecom service based on historical customer data.  
Machine learning classification models are used to analyze customer behavior and identify key factors contributing to churn.

---

## 📌 Problem Statement
Customer churn is a major challenge for subscription-based businesses.  
The objective of this project is to:
- Predict customer churn using historical data
- Understand important factors influencing customer decisions
- Help businesses take preventive actions to reduce churn

---

## 📂 Dataset
- **Dataset Name:** Telco Customer Churn
-   Link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- **File:** `churn.csv`
- **Target Variable:** `Churn` (Yes / No)
- **Features Include:**
  - Customer demographics (gender, senior citizen, dependents)
  - Services subscribed (Internet, phone, streaming, security)
  - Account information (tenure, contract type, payment method)
  - Billing details (monthly charges, total charges)

---

## ⚙️ Models Used
The following classification models were implemented and compared:

1. **Logistic Regression**
   - Used as a baseline model
   - Provides interpretability and probability-based predictions

2. **Random Forest Classifier**
   - Ensemble-based model
   - Captures complex patterns and feature interactions
   - Final model used for prediction

---

## 🧪 Model Evaluation
Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

Random Forest achieved better performance compared to Logistic Regression.

---

## 🔍 Sample Prediction
The trained model can predict churn for individual customers from the test dataset and classify them as:
- **Yes** → Customer is likely to churn
- **No** → Customer is likely to stay

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab

---

## 📁 Project Structure
```

Customer-Churn-Prediction/
│
├── Images/
├── .gitattributes
├── Churn.csv
├── Customer_Churn_Prediction.ipynb
├── README.md
└── Requirements.txt

```

---

## 🚀 How to Run the Project
1. Clone the repository
2. Install dependencies using:
```

pip install -r requirements.txt

```
3. Open the Jupyter Notebook:
```

Customer_Churn_Prediction.ipynb

```
4. Run all cells to train and evaluate the model

---

## 📌 Conclusion
This project demonstrates how machine learning models can be effectively used to predict customer churn and support data-driven business decisions.

---

## 👤 Author
**Aman Sah**  
Intern at Codec Technologies
