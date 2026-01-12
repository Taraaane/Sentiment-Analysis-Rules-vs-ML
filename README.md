# Sentiment Analysis: Rules vs. Machine Learning 📊

This project was developed as part of a university assignment to compare two different approaches to Natural Language Processing (NLP).

## 🚀 Project Overview
The goal is to classify text sentiment (Positive, Negative, Neutral) using two distinct methods:
1. **Rule-Based System:** Built using a custom lexicon (dictionary) and Python Regular Expressions (Regex) to handle negations and intensifiers.
2. **Machine Learning Model:** Implemented using **Logistic Regression** from the `scikit-learn` library.

## 🛠️ Key Features
- **Lexicon-Based Logic:** Custom rules for handling "not" (e.g., "not good") and intensifiers (e.g., "very happy").
- **Data Preprocessing:** Lowercasing and tokenization using Regex.
- **Model Evaluation:** Direct comparison of accuracy between human-defined rules and statistical learning.

## 📈 Results
- **Rule-based Accuracy:** [0.535]
- **ML Accuracy:** [0.845]
The Machine Learning approach generally performed better as it could learn complex patterns beyond simple word matching.

## 🐍 Libraries Used
- Python 3.x
- Pandas
- Scikit-learn
- Re (Regular Expressions)# Sentiment-Analysis-Rules-vs-ML
A comparative study of Sentiment Analysis using Regex and Logistic Regression in Python
