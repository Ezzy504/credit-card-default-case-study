# credit-card-default-case-study
"A data science case study predicting credit card defaults using CRISP-DM methodology and machine learning."

# Credit Card Default Prediction – Data Science Case Study

This is a complete end-to-end machine learning case study to predict customer defaults using the CRISP-DM methodology.

## 📌 Problem Statement
Can we accurately predict which credit card customers are likely to default on their next payment? The goal is to help financial institutions reduce credit risk and proactively flag high-risk customers.

## 🧠 Methodology
This project follows the **CRISP-DM** approach:
1. **Business Understanding**
2. **Data Understanding**
3. **Data Preparation**
4. **Modeling**
5. **Evaluation**
6. **Deployment Strategy**

## 📊 Data Source
- **Dataset**: UCI Credit Card Default Dataset (30,000+ customers)
- **Target**: `default.payment.next.month` (0 = no default, 1 = default)

## 🤖 Models Compared

| Model                | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 81.5%    | 75%       | 61%    | 67.3%    |
| Random Forest       | 83.2%    | 72%       | 68%    | 70.2%    |
| SVM (RBF Kernel)    | 82.4%    | 74%       | 66%    | 69.8%    |
| **XGBoost**         | **84.1%**| **76%**   | **70%**| **72.9%**|

📌 **Best Model**: XGBoost due to better handling of class imbalance and ROC-AUC = 0.88.

## 📈 Evaluation Visuals

- ROC Curve  
- Confusion Matrix  
- Feature Importance from XGBoost  

*(See the `/images/` folder for charts)*

## 🛠 Tools Used

- Python, Pandas, NumPy, Scikit-learn
- XGBoost
- Jupyter Notebook
- Canva (for report design)

## 📘 Final Report

View the full PDF report:  
📎 [`Data science case study.pdf`](./Data%20science%20case%20study.pdf)

## 🔗 Author

- Pratishtha Srivastava  



