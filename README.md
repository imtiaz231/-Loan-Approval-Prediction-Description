# -Loan-Approval-Prediction-Description
✅ Task Overview

Predict loan approvals with machine learning! This project helps financial institutions automate loan decisions while handling real-world data challenges.

🌟 Features
🔄 Data Preprocessing: Auto-handles missing values & categorical features

⚖️ Class Imbalance: Uses SMOTE to balance approval/rejection data

🤖 Multiple Models: Compares Logistic Regression 📈 vs Decision Tree 🌳

📊 Smart Metrics: Focuses on precision, recall & F1-score (not just accuracy!)

🔍 Explainable AI: Shows which factors most impact loan decisions


📂 Dataset
Using the popular Loan Approval Prediction Dataset from Kaggle:

📝 614 loan applications

🔢 12 features including:

💰 Income & employment details

🎓 Education level

📅 Credit history

🎯 Target: Loan approval status (✅ Approved/❌ Rejected)

⚙️ Methodology
🔄 Data Pipeline
🧩 Fix missing values (median/mode)

🔢 Scale numerical features

🏷️ One-hot encode categories

🤖 Modeling
Baseline Models

SMOTE-enhanced versions

Evaluated using:

✅ Precision

🔄 Recall

✨ F1-Score

📊 Confusion matrices

🔍 Key Insights
"Credit history is 3x more important than income for approvals!"

📈 Results
Model	Precision	Recall	F1-Score
📈 Logistic Regression	0.96	0.58	0.72
🌳 Decision Tree	0.72	0.61	0.66
📈+SMOTE	0.89	0.65	0.76✅
🌳+SMOTE	0.81	0.68	0.74 
Best Model: Logistic Regression  🏆

