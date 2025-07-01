# Electricity_Bill_Fraud_Detection

This project aims to detect fraudulent electricity consumption behavior using classical machine learning techniques. It simulates realistic electricity usage data for 1,000 users over 12 months, introduces intentional fraud, and applies a Random Forest Classifier to identify suspicious patterns — all without using deep learning.

📌 Key Features

🔧 Simulated Dataset: Created a synthetic dataset representing monthly electricity consumption with embedded fraudulent behavior.

📊 Feature Engineering: Designed a custom UsageDeviation metric to quantify abnormal usage.

🤖 Modeling: Trained a RandomForestClassifier using Scikit-learn for binary classification (fraud vs. normal).

📈 Visualization: Used Matplotlib to clearly show differences in usage patterns between normal and fraudulent users.

🛠️ Tech Stack

Python

NumPy

Pandas

Matplotlib

Scikit-learn
