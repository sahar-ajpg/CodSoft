.

🚨 Credit Card Fraud Detection using Machine Learning
📌 Project Overview

Credit card fraud is a serious financial problem that results in significant monetary losses worldwide. Since fraudulent transactions are rare compared to legitimate transactions, detecting fraud is a challenging machine learning problem involving highly imbalanced data.

This project builds and compares machine learning models to accurately detect fraudulent transactions while minimizing false negatives.

🎯 Problem Statement

The objective of this project is to develop a binary classification model that can distinguish between legitimate and fraudulent credit card transactions.

0 → Legitimate transaction

1 → Fraudulent transaction

Since fraud cases are extremely rare, traditional accuracy is not a reliable evaluation metric. Instead, the focus is placed on Recall, Precision, F1-Score, and ROC-AUC.

📊 Dataset Description

The dataset contains anonymized credit card transactions.

Features:

Time – Time elapsed between transactions

V1 – V28 – PCA-transformed features (confidential banking data)

Amount – Transaction amount

Class – Target variable (0 = Normal, 1 = Fraud)

⚠ The dataset is highly imbalanced, with fraud transactions forming a very small percentage of total transactions.

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🤖 Models Implemented

Logistic Regression

Random Forest Classifier

📈 Model Evaluation

Since the dataset is imbalanced, the following metrics were used:

Confusion Matrix

Precision

Recall

F1-Score

ROC-AUC Score

Results:

Logistic Regression ROC-AUC ≈ 0.95

Random Forest ROC-AUC ≈ 0.96

Random Forest slightly outperformed Logistic Regression and was selected as the final model.

📌 Key Learnings

Handling imbalanced datasets

Importance of Recall in fraud detection

Why accuracy is misleading in imbalanced classification

Model comparison and evaluation

End-to-end machine learning workflow

🧠 Why Accuracy Is Not Used?

Because the dataset is highly imbalanced, a model predicting all transactions as legitimate could still achieve over 99% accuracy while completely failing to detect fraud.

Therefore, Recall and ROC-AUC are more reliable performance indicators.

🚀 Conclusion

The Random Forest model achieved strong fraud detection performance with a ROC-AUC score of approximately 0.96. The model successfully identifies fraudulent transactions while minimizing missed fraud cases.

This project demonstrates practical application of machine learning in real-world financial fraud detection systems.
