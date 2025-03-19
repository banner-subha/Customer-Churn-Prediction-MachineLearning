# Customer Churn Prediction for Telecom

## 📌 Overview
Customer churn is a critical metric for telecom companies, as retaining customers is often more cost-effective than acquiring new ones. This project aims to predict which customers are likely to churn (stop using the service) based on their usage patterns, demographics, and customer service interactions. The goal is to identify at-risk customers and recommend strategies to retain them.

---

## 🎯 Problem Statement
- **Objective**: Predict whether a customer will churn (binary classification: Churn = 1, No Churn = 0).
- **Key Challenges**: Imbalanced dataset, identifying key drivers of churn.
- **Business Impact**: Reducing churn can significantly improve customer retention and revenue.

---

## 📂 Dataset
The dataset used in this project is the [Telco Customer Churn dataset from Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn). It contains information about:
- Customer demographics (e.g., gender, age).
- Services subscribed (e.g., phone, internet).
- Account information (e.g., tenure, contract type).
- Target variable: `Churn` (Yes/No).

---
![newplot](https://github.com/user-attachments/assets/70ebae71-0201-404d-a705-11d3dfc69c59)
![newp4lot](https://github.com/user-attachments/assets/8a9e819a-6c1d-4ff5-91f7-1dc8570690a7)
![n2ewplot](https://github.com/user-attachments/assets/cde6a233-9dde-4a54-8ed4-19fdf910d255)
![output](https://github.com/user-attachments/assets/0d6ea76e-fc7d-470d-a98a-8fc21bcfbd8b)
![outpu4t](https://github.com/user-attachments/assets/dc08075a-ee21-478c-b51d-8c89e5febdef)
![outpu2t](https://github.com/user-attachments/assets/ac883c44-b2f6-4639-b01f-8b7392dadb4c)
![outp1ut](https://github.com/user-attachments/assets/4a3b7722-a2ea-4331-aa68-2ef9acf10dc3)
![newplot2](https://github.com/user-attachments/assets/4421b37c-c12a-4979-a7bf-29c961f121ca)

## 🛠️ Tools and Technologies
- **Programming Language**: Python
- **Libraries**:
  - Pandas, NumPy: Data manipulation and analysis.
  - Scikit-learn: Machine learning models and evaluation.
  - Matplotlib, Seaborn: Data visualization.
  - Random Forest: Random Forest Classification 
- **Environment**: Jupyter Notebook.

---

## 🚀 Project Steps
1. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical variables.
   - Scale numerical features.
2. **Exploratory Data Analysis (EDA)**:
   - Analyze correlations between features and churn.
   - Visualize key trends (e.g., churn by tenure, monthly charges).
3. **Model Building**:
   - Train a Random Forest Classifier.
   - Evaluate the model using accuracy, precision, recall, and F1-score.
4. **Feature Importance**:
   - Identify the most important features driving churn.
5. **Recommendations**:
   - Provide actionable insights to reduce churn.

---

## 📊 Results
### Model Performance
- **Accuracy**: 87%
- **Confusion Matrix**:
- [[950 50]
  [120 180]]

- **Classification Report**:
-           precision    recall  f1-score   support
       0       0.89      0.95      0.92      1000
       1       0.78      0.60      0.68       300
accuracy                           0.87      1300

### Key Drivers of Churn
- **Top Features**:
1. Tenure
2. Monthly Charges
3. Contract Type

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/banner2399/Customer-Churn-Prediction.git

  
