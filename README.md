
# Credit Card Fraud Detection using ML

## 📌 Overview
A machine learning project to detect fraudulent credit card transactions using various models and handle data imbalance with SMOTE.

## 📂 Dataset
- Source: [Kaggle - Credit Card Fraud](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- 284,807 transactions with only 492 frauds

## 🛠️ Workflow
1. Data Loading + Preprocessing
2. Exploratory Data Analysis (EDA)
3. Handling Class Imbalance with SMOTE
4. Model Training (LogReg, RF, XGBoost)
5. Evaluation and Visualizations

## 📈 Results
| Model              | Recall (Class 1) | Precision | F1-score | AUC  |
|-------------------|------------------|-----------|----------|------|
| Logistic Regression |       0.06      |   0.93    |  0.11   |     0.9786         
| Random Forest       |      0.92       |   0.84    | 0.88    |     0.9914
| XGBoost             |        0.73     | 0.85      | 0.78    |     0.9883

## 📌 Key Learnings
- Importance of handling imbalanced data
- Use of ROC-AUC in fraud detection
- SMOTE vs class weights

## 💻 Tools Used
- Python, scikit-learn, XGBoost, imbalanced-learn
- Jupyter Notebook / Google Colab


