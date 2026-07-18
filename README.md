# Fake News Classification using NLP and Machine Learning

## Overview

This project implements a machine learning based text classification system to classify news articles as **Fake** or **Real** using Natural Language Processing (NLP) techniques.

The model uses **TF-IDF Vectorization** to convert text into numerical features and **Logistic Regression** as the classification algorithm.

The objective of this project is to build an NLP pipeline that can analyze news article content and classify it based on patterns learned from a labeled dataset.

---

## Features

- Text preprocessing and cleaning
- Lowercase conversion
- Special character removal
- Extra whitespace removal
- Stopword removal
- Stemming using Porter Stemmer
- TF-IDF feature extraction
- Logistic Regression classification
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

---

## Dataset

Dataset used:

[Kaggle Fake News Detection Dataset](PASTE_KAGGLE_LINK_HERE)

The dataset contains labeled news articles categorized as:

- `0` → Fake News
- `1` → Real News

The dataset file is not included in this repository due to size limitations.

---

### The model is trained on a specific news dataset and may not generalize to all types of misinformation outside the training domain.
