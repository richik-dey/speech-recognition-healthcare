# Amazon Product Reviews Sentiment Analysis Using Machine Learning

This project performs **binary sentiment classification** (Positive/Negative) on Amazon product reviews using traditional machine learning algorithms. The goal is to help businesses understand customer satisfaction based on review content.

## 📌 Project Overview

- **Domain:** Natural Language Processing (NLP)
- **Techniques:** Text Preprocessing, TF-IDF Vectorization, Supervised Machine Learning
- **Algorithms Used:** Logistic Regression, Naive Bayes, Support Vector Machine, Random Forest, Decision Tree, K-Nearest Neighbor
- **Best Accuracy:** Random Forest – 90.37%

## 🧠 Workflow

1. Load and clean review data
2. Preprocess text (remove HTML, punctuation, digits, etc.)
3. Convert text to vectors using TF-IDF
4. Split data into training and testing sets
5. Train 6 ML models and evaluate performance
6. Visualize results using Confusion Matrix and ROC-AUC

## 🔧 Tools & Libraries

- Python (Google Colab)
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- WordCloud

## 📁 Repository Structure

amazon-sentiment-analysis/
├── sentiment_analysis.ipynb # Jupyter/Colab notebook
├── balanced.csv # Balanced dataset of reviews (optional)
├── requirements.txt # Python dependencies
├── report/ # Final project report (PDF/DOCX)
└── README.md # Project overview
