# bank-marketing-prediction-decision-tree
Bank Marketing Prediction using Decision Tree

# 🔍 Problem Statement

Can we predict whether a customer will subscribe to a term deposit offer based on their demographic and behavioral information?

This project builds a Decision Tree classifier to predict customer responses using real-world marketing campaign data from a Portuguese bank.

# 📁 Dataset Overview

Source: UCI Bank Marketing Dataset

Records: 45,211

Features: Age, Job, Marital Status, Education, Balance, Loan Status, Campaign Info, etc.

Target Variable: y — whether the customer subscribed (yes) or not (no)

# 📊 Features Used

Some features were dropped due to:

High potential for data leakage (duration)

Low predictive value (contact, default, day, etc.)

# Final Features Used:

age, marital, education, balance, housing, loan, month, campaign, pdays, previous, poutcome, etc.

# Preprocessing:

Categorical features were encoded using OneHotEncoder

A Pipeline combined preprocessing + model training

# 🧠 Model

Algorithm: Decision Tree Classifier (Scikit-learn)

Depth: Limited to 4 to prevent overfitting

Split: 80% training / 20% testing

Tools: Pandas, Scikit-learn, Matplotlib

# 🌟 Results

Accuracy: (Fill in your result)

# Insights:

Most influential features: (e.g., balance, housing, previous outcomes)

Model interpretable via decision paths

# 📘 What I Learned

Real-world data preprocessing and cleanup

Handling categorical data with pipelines

Visualizing tree-based models with plot_tree

Understanding feature importance

# 📢 Shareable Version

This project is also shared visually on LinkedIn using a custom Canva template.

# 💼 How to Run

pip install -r requirements.txt
jupyter notebook notebooks/bank_tree_model.ipynb

# 🔗 Links

Dataset: UCI Bank Marketing Data

Visual Post: (Link to your LinkedIn or Canva post)

# ✅ Next Steps

Test with Random Forest or Gradient Boosting

Perform hyperparameter tuning

Deploy via Streamlit or Flask

# © License

MIT License (or choose another as you prefer)
