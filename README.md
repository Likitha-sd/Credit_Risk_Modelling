📊 Credit Risk Modelling with Explainable AI
📌 Overview
This project builds and deploys a machine learning model to predict whether a bank customer is a good or bad credit risk.
It leverages Logistic Regression, Decision Trees, Random Forest, and XGBoost, integrated into a Streamlit web application for real‑time scoring.

The goal is to demonstrate end‑to‑end ML deployment in a banking/fintech context, with a focus on risk management and compliance.

🎯 Features
Predicts credit risk based on customer attributes (Age, Job, Housing, Saving/Checking accounts, Credit Amount, Duration, Purpose).

Interactive Streamlit app for real‑time customer scoring.

Modular pipeline for data preprocessing, model training, and evaluation.

Ready for explainability integration (SHAP/LIME) to meet regulatory requirements.

Scalable design for handling large datasets.

🛠 Tech Stack
Python 3.9+

Libraries: pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn, streamlit, joblib

Deployment: Streamlit (local or cloud hosting)

Dataset: German Credit Risk dataset / custom bank dataset

📂 Project Structure
Code
├── data/                # Raw dataset (e.g., data.csv)
├── notebooks/           # Jupyter notebooks for EDA
├── models/              # Trained models (.pkl/.joblib)
├── scripts/             # Preprocessing & training scripts
├── app.py               # Streamlit app for deployment
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
🚀 How to Run
Clone the repository:

bash
git clone https://github.com/yourusername/credit-risk-modelling.git
cd credit-risk-modelling
Install dependencies:

bash
pip install -r requirements.txt
Run the Streamlit app:

bash
streamlit run app.py
Open the app in your browser at http://localhost:8501.

📊 Results
Achieved ~87% accuracy using XGBoost.

Streamlit app provides real-time predictions.

Planned integration of SHAP explainability for transparent decision-making.

📌 Future Work
Add SHAP/LIME explainability to highlight feature importance.

Build dashboard layer for customer risk segmentation.

Optimize inference speed for large-scale deployment.

🏦 Business Impact
This project demonstrates how banks can:

Automate credit scoring.

Improve risk management.

Ensure regulatory compliance with explainable AI.
