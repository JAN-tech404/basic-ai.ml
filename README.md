🚀 Hello World of Data Science & AI

This repository contains a collection of four Jupyter Notebook (.ipynb) projects focused on Exploratory Data Analysis (EDA), Natural Language Processing (NLP), and Predictive Machine Learning.
📌 Projects Overview
1. 🌸 Iris Dataset Exploratory Analysis

Description: Performs a deep dive into the classic Iris flower dataset to identify patterns and relationships between species.

    Features: Automated profiling, distribution density (KDE), and outlier analysis.

    Visualizations: Pairplots, Histograms, and Boxplots for species differentiation.

    Tech Stack: pandas, matplotlib, seaborn.

2. 🏥 AI General Health Query Chatbot

Description: A conversational agent powered by the Llama-3-8B model via the Hugging Face Inference API.

    Features: Natural Language Understanding, emergency detection guardrails, and color-coded UI.

    Setup: Requires a Hugging Face Access Token (Read permissions).

    Safety: Hard-coded AI disclaimers and emergency service redirects.

    ⚠️ MEDICAL DISCLAIMER: This bot is an AI assistant, not a doctor. It does not provide medical diagnoses or professional advice.

3. ❤️ Heart Disease Prediction & Analysis

Description: A healthcare analytics pipeline that cleans clinical data and predicts heart disease presence.

    Features: Missing value handling, correlation heatmaps, and feature importance ranking.

    Model: Logistic Regression with feature scaling.

    Evaluation: Accuracy scores, Confusion Matrices, and ROC/AUC curves.

4. 📈 Stock Price Prediction (Random Forest)

Description: A financial forecasting tool that predicts the next day's closing price for Tesla (TSLA) using historical market data.

    Features: Real-time data retrieval via yfinance and feature engineering (OHLCV).

    Model: Random Forest Regressor.

    Analysis: Time-series plots comparing actual vs. predicted market trends.

    ⚠️ FINANCIAL DISCLAIMER: This script is for educational purposes only and should not be used as the basis for real-world investment decisions.

🛠️ Installation & Requirements

To run these notebooks, ensure you have Python 3.8+ installed along with the following libraries:
Bash

pip install pandas numpy seaborn matplotlib scikit-learn huggingface_hub yfinance

🚀 How to Run

    Open your terminal or command prompt.

    Launch Jupyter Lab or Notebook:
    Bash

    jupyter notebook

    Open the desired .ipynb file.

    For the Health Chatbot, ensure you replace the YOUR_HF_TOKEN placeholder with your actual Hugging Face token.

    For Heart Disease Prediction, ensure a heart.csv file is located in the same directory as the notebook.

    Execute the cells in order to generate insights and visualizations.

Developed as part of a Data Science & AI Task Series.
