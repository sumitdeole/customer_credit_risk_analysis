### Credit Risk Modeling with Expert LLM Reporting
This project demonstrates an end-to-end workflow for credit risk classification using three robust machine learning models:
- Random Forest
- XGBoost
- Deep Learning
The primary goal is to maximize recall, ensuring high-risk customers are not misclassified as low-risk. The workflow addresses class imbalance using SMOTE and provides automated, expert-level interpretation of results using a local LLM (Mistral via Ollama).


#### Data
**Source:** (Kaggle - Credit Risk Customers)[https://www.kaggle.com/datasets/ppb00x/credit-risk-customers/data]
**Description:** Contains demographic, financial, and credit history data for customers. The target variable, class, indicates whether a customer is high risk (bad) or low risk (good).