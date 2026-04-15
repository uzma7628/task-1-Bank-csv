# task-1-Bank-csv
This project implements a Bank Marketing Prediction system to identify potential customers for term deposit subscriptions. Using the UCI Bank Marketing dataset, I developed a classification pipeline using the Random Forest algorithm. 
# Bank Marketing: Term Deposit Subscription Prediction 🏦

This project focuses on predicting whether a bank customer will subscribe to a term deposit based on marketing campaign data. By using Machine Learning, we aim to help banks target the right customers, saving time and increasing conversion rates.

##  Project Objective
The goal is to build a classification model that predicts the target variable `y` (yes/no) and provides transparency into "why" a customer is likely to subscribe using **Explainable AI (XAI)**.

##  Dataset Overview
The dataset is sourced from the **UCI Machine Learning Repository** (Bank Marketing Dataset). It contains information about:
- **Customer Profiles:** Age, Job, Marital Status, Education, Balance.
- **Marketing Contacts:** Contact type, Day, Month, and Duration of the call.
- **Previous Campaigns:** Number of contacts performed and previous outcomes.

##  Technical Workflow
1. **Data Exploration & Cleaning:** Checking for null values and understanding feature distributions.
2. **Feature Encoding:** Converted categorical text data into numerical format using **One-Hot Encoding** (pd.get_dummies).
3. **Model Training:** Implemented a **Random Forest Classifier** to handle complex non-linear relationships.
4. **Model Evaluation:** Evaluated performance using:
   - **Confusion Matrix** (to see True Positives vs False Negatives).
   - **F1-Score** (to balance precision and recall).
   - **Accuracy Score**.
5. **Model Interpretability (XAI):** Used **SHAP (SHapley Additive exPlanations)** to visualize which features (like call duration or age) most influenced the model's prediction for individual customers.

##  Key Insights
- **Call Duration:** Longer conversations strongly correlate with successful subscriptions.
- **Previous Outcome:** Customers who subscribed in previous campaigns are more likely to subscribe again.
- **Explainability:** SHAP plots reveal that the model doesn't just guess; it relies on logical customer behavior patterns.

##  Skills Demonstrated
- Python (Pandas, NumPy)
- Machine Learning (Scikit-Learn)
- Data Visualization (Matplotlib, Seaborn)
- Explainable AI (SHAP/LIME)

---
Developed as part of my Data Science Portfolio. 🚀
