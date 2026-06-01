## 💳 Credit Risk Prediction App

### Streamlit Live Link

https://creditriskmodelling-qxqxjzz64utmh8ckugqpeu.streamlit.app/

### App Demo Image

<img width="1026" height="906" alt="Screenshot_1-6-2026_181331_localhost" src="https://github.com/user-attachments/assets/8e9460eb-19d8-4249-b612-919dfbbaf4a6" />


## 🔍 Overview

This project is an end-to-end Machine Learning application that predicts whether a loan applicant is a Good Credit Risk or Bad Credit Risk.
It combines data preprocessing, model training, hyperparameter tuning, and deployment into a user-friendly Streamlit app.

##⚙️ Tech Stack

Python: pandas, numpy, seaborn, matplotlib

 Machine Learning: scikit-learn (Decision Tree, Random Forest, Extra Trees), XGBoost

 Model Persistence: joblib

#Deployment: Streamlit

# 📂 Project Structure
Code
├── app.py                        # Streamlit app
├── german_credit_data.csv        # Dataset
├── extra_trees_credit_model.pkl  # Trained Extra Trees model
├── Sex_encoder.pkl               # Label encoder for Sex
├── Housing_encoder.pkl           # Label encoder for Housing
├── Saving accounts_encoder.pkl   # Label encoder for Saving accounts
├── Checking account_encoder.pkl  # Label encoder for Checking account
├── target_encoder.pkl            # Label encoder for Risk
└── README.md                     # Documentation

## 🚀 How to Run

# Clone the repository:

# bash
git clone <repo-url>
cd Credit-Risk-Prediction
Install dependencies:

# bash
pip install -r requirements.txt
Run the app:

# bash
streamlit run app.py

## Open in browser:

# Local:
http://localhost:8501

# Network: 
http://<your-ip>:8501

## 🖥️ Usage

Enter applicant details:

Age, Sex, Job, Housing, Saving Accounts, Checking Account, Credit Amount, Duration

Click Predict Risk

## Output:

✅ GOOD Credit Risk

❌ BAD Credit Risk

## 📈 Model Performance

Model	Accuracy	Notes
Decision Tree	~58%	Simple baseline
Random Forest	~62%	Ensemble improvement
Extra Trees	~65%	Best performing model
XGBoost	~67%	Strong but heavier


## 👉 Final deployed model: Extra Trees Classifier

## 🌟 Key Highlights
End-to-end ML pipeline: EDA → Feature Engineering → Model Training → Deployment

Encoders saved with joblib for categorical features

Interactive Streamlit app for real-time predictions

Demonstrates fintech + AI skills relevant to credit scoring and risk management

## 📸 Demo Screenshot

