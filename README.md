# 🕵️ Fraud Detection Using Machine Learning

A complete end-to-end Machine Learning project that detects fraudulent financial transactions using a trained classification model.
The project includes:

✔ Data analysis
✔ Feature engineering
✔ Model training
✔ ML pipeline creation
✔ Exporting the model as .pkl
✔ Deployment-ready Streamlit application
# 📊 Project Description
This project aims to detect fraudulent transactions using machine learning.
The dataset contains details about:
Transaction amount
Old and new balance (sender)
Old and new balance (receiver)
Transaction type
The target variable:
isFraud → 1 = Fraud, 0 = Non-Fraud
We train a machine learning pipeline using:
StandardScaler (for numeric features)
OneHotEncoder (for categorical features)
Logistic Regression or other ML models
Packed into a Pipeline for clean deployment
The trained pipeline is exported as .pkl using joblib.
# 🧪 Technologies Used
Languages: Python 3.12+
Libraries: pandas, numpy, scikit-learn, joblib, streamlit, matplotlib & seaborn (for EDA)
Tools: Jupyter Notebook, VS Code, Git, GitHub
# 📈 EDA Summary (Exploratory Data Analysis)
Performed inside the Jupyter notebook:
Checked missing values
Visualized distributions
Correlation analysis
Detected class imbalance
Derived effective feature transformations
# 🤖 Model Training
The model training process includes:
1. Splitting dataset into train/test
2. Creating feature groups
3. Applying transformations:
4. Training classifier:
5. Exporting model:
# 🖥️ Streamlit App
The Streamlit UI allows you to input:
Transaction type
Amount
Sender balances
Receiver balances
And predicts:
✔ Fraud
✔ Not Fraud

This file contains:
Preprocessing (scaling + encoding)
Trained machine learning classifier
Feature mapping

# 🌐 Future Enhancements
Deploy on Streamlit Cloud / Render
Add more classification models (XGBoost, RandomForest)
Improve UI/UX
Add data drift detection
Add model explainability (SHAP)

# 🙋 Author
Sahar (Arun Sah)
Fraud Detection ML Engineer
GitHub: https://github.com/Arunsah56
