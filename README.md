🛡️ Microsoft: Classifying Cybersecurity Incidents with ML
A machine learning solution to classify cybersecurity incidents (TP, BP, FP) using Microsoft’s GUIDE dataset. The project aims to support Security Operation Centers (SOCs) by automating triage and enabling faster threat response.

🎯 Objective
Build a robust classification model that predicts incident triage grades based on historical evidence and customer responses. Evaluate performance using macro-F1 score, precision, and recall.

📁 Dataset
Source: GUIDE dataset (Microsoft)

Classes: True Positive (TP), Benign Positive (BP), False Positive (FP)

Structure: Multi-level hierarchy — evidence → alert → incident

🛠 Tech Stack
Python (Pandas, NumPy, Scikit-learn)

XGBoost, LightGBM, Logistic Regression

SHAP (Feature Importance)

Git for version control

🧠 Approach
🔍 EDA & Preprocessing: Handle missing data, encode features, scale numerics

🔄 Data Split: Stratified train-validation-test

🤖 Modeling: Train baseline and advanced models (RF, XGB, etc.)

🧪 Evaluation: Use macro-F1, precision, recall

⚖️ Class Imbalance: SMOTE, class weighting

🔍 Interpretability: Feature importance, error analysis

✅ Deliverables
📂 Source code (clean and modular)

🧠 Trained classification model

📊 Evaluation results and visual insights

📄 Documentation with business recommendations

