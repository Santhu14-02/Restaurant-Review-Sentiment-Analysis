# 🍽️ Restaurant Review Sentiment Analysis using NLP

This project performs **Sentiment Analysis** on restaurant reviews using **Natural Language Processing (NLP)** and **Machine Learning**.

## 📌 Project Overview

The goal of this project is to classify restaurant reviews as **Positive** or **Negative**.

The project includes:
- Text preprocessing
- Stopword removal
- Stemming
- Bag of Words (BoW)
- Feature Engineering using Bigrams
- Model Training & Evaluation

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn

---

## 🔄 Workflow

Restaurant Reviews
→ Text Cleaning
→ Lowercasing
→ Stopword Removal
→ Stemming
→ Bag of Words
→ Logistic Regression
→ Sentiment Prediction

---

## 🤖 Models Used

- Naive Bayes
- Logistic Regression

---

## 📊 Results

| Model | Accuracy |
|--------|----------|
| Naive Bayes | 73% |
| Logistic Regression | 77.5% |
| Logistic Regression + Bigrams | **79%** ✅ |

---

## 💡 Key Learning

Adding **Bigrams (`ngram_range=(1,2)`)** improved the model by capturing phrases such as **"not good"** instead of treating **"not"** and **"good"** as independent words.

---

## 🚀 Future Improvements

- TF-IDF
- Word Embeddings (Word2Vec/GloVe)
- BERT
- Transformer Models
