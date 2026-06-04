# Emotion Text Classifier

## Overview

Emotion Text Classifier is a Natural Language Processing (NLP) project that predicts emotions from textual input using Machine Learning algorithms. The project implements a complete text classification pipeline including data preprocessing, feature extraction, model training, and performance evaluation.

The system can classify text into multiple emotion categories such as happiness, sadness, anger, fear, love, surprise, and more.

---

## Features

- Text cleaning and preprocessing
- Lowercasing text
- Punctuation removal
- Number removal
- Emoji removal
- Stopword filtering using NLTK
- Feature extraction using:
  - Bag-of-Words (Count Vectorizer)
  - TF-IDF Vectorizer
- Machine Learning models:
  - Multinomial Naive Bayes
  - Logistic Regression
- Model performance evaluation
- Multi-class emotion classification

---

## Tech Stack

- Python
- Scikit-learn
- NLTK
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Workflow

### 1. Data Collection
Load the emotion dataset containing text samples and corresponding emotion labels.

### 2. Data Preprocessing

The following preprocessing steps are applied:

- Convert text to lowercase
- Remove punctuation
- Remove numbers
- Remove emojis
- Remove stopwords
- Clean extra spaces

Example:

Input:
