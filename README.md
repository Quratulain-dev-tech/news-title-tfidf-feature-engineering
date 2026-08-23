# 📊 News Title TF-IDF Feature Engineering

> A clean and reproducible Natural Language Processing (NLP) feature-engineering pipeline for converting 5,000 news article titles into numerical TF-IDF features.

---

## 🚀 Project Overview

This project performs **TF-IDF (Term Frequency–Inverse Document Frequency)** feature engineering on a dataset containing **5,000 news article titles**.

The purpose of the project is to transform raw text titles into meaningful numerical features that can be used by Machine Learning and NLP models.

The pipeline is designed to be:

- Clean
- Reproducible
- Validated
- Memory-efficient
- Easy to understand
- Suitable for further Machine Learning workflows

---

## 🎯 Objective

The main objective of this project is to apply **TF-IDF feature engineering** to news article titles while preserving the original titles and maintaining complete document coverage.

The pipeline converts textual news titles into numerical representations where each word or phrase receives a TF-IDF score based on its importance across the dataset.

---

## 📂 Project Structure

```text
feature-engineering/
│
├── tfidf.py
├── news_titles_tfidf.csv
├── tfidf_matrix.npz
├── tfidf_vectorizer.joblib
└── README.md
