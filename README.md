# Sentimental-Analysis-of-Tweeter-Dataset
# 🐦 Sentiment Analysis on Twitter Reviews

This project performs sentiment analysis on tweets using the [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140) dataset. It classifies tweets as **positive** or **negative** using text preprocessing and a Logistic Regression model.

---

## 🔍 Overview

The goal of this project is to:
- Preprocess raw Twitter data using NLP techniques (stemming, stopword removal, etc.)
- Convert text into numerical features using TF-IDF
- Train a machine learning model to predict sentiment
- Evaluate model performance
- Save and reload the model for future predictions

---

## 📁 Dataset

- **Source:** [Kaggle - Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)
- **Description:** 1.6 million tweets labeled as:
  - `0` for **negative**
  - `4` for **positive** (converted to `1` in preprocessing)

---

## 🧠 Model

- **Algorithm:** Logistic Regression
- **Libraries used:** `scikit-learn`, `NLTK`, `pandas`, `numpy`
- **Accuracy:**
  - Training: ~77.6%
  - Test: ~77.6%

---

## 📦 Installation

```bash
# Clone this repository
git clone https://github.com/your-username/twitter-sentiment-analysis.git
cd twitter-sentiment-analysis

# Install dependencies
pip install -r requirements.txt
