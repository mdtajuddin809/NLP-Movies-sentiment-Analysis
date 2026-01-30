# 🎬 NLP Movie Sentiment Analysis

This project performs sentiment analysis on movie overviews using Natural Language Processing (NLP) techniques.

## 📌 Objective
To classify movie descriptions as **Positive** or **Negative** based on textual content.

## 📊 Dataset
- Source: Top Rated Movies Dataset
- Columns used:
  - overview (text)
  - vote_average (used to generate sentiment labels)

## ⚙️ Methodology
1. Text Cleaning (lowercasing, stopword removal, lemmatization)
2. Feature Extraction using TF-IDF
3. Sentiment Labeling based on movie ratings
4. Model Training using Logistic Regression
5. Model Evaluation using accuracy and classification report

## 🧠 Model Used
- Logistic Regression

## 📈 Results
- Achieved ~75–80% accuracy after proper preprocessing and labeling.

## 🚀 How to Run
```bash
pip install -r requirements.txt
python src/train_model.py
