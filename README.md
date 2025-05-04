# Tweet Sentiment Analysis using BERT and Traditional ML Models

This project performs **sentiment classification** of tweets into *positive*, *negative*, or *neutral* using both traditional Machine Learning techniques and **BERT**, a transformer-based model known for its superior NLP performance.

---

## 🧠 Project Overview

With the massive rise in social media content, understanding public sentiment in tweets is invaluable. This project explores both classical approaches and state-of-the-art deep learning (BERT) to analyze sentiments from Twitter text data.

---

## 🛠️ Features

- 🧹 Text Preprocessing: Cleaning, stopword removal, stemming, tokenization.
- 📐 Feature Extraction: CountVectorizer, TF-IDF, and **BERT embeddings**.
- 🤖 Models Implemented:
  - Logistic Regression
  - Naive Bayes
  - SVM
  - Random Forest
  - **BERT (Bidirectional Encoder Representations from Transformers)**
- 📊 Evaluation Metrics: Accuracy, Confusion Matrix, F1-Score, Precision, Recall

---

## 🔍 Model Performance

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 79.4%   |
| Naive Bayes         | 75.6%   |
| SVM                 | 78.3%   |
| Random Forest       | 76.1%   |
| **BERT**            | **90.25%** ✅ |

> ✅ **BERT** significantly outperforms traditional models due to its deep contextual understanding of language.
