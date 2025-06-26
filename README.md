# 🚨 Sentiment Analysis of Tweets for Hate Speech Detection

This project aims to classify tweets based on whether they contain **hate speech**, specifically **racist** or **sexist** content. It is framed as a **binary classification task**.

---

## 📌 Objective

Given a dataset of tweets labeled as either hateful (`1`) or not hateful (`0`), the objective is to build models that can accurately identify **racist or sexist tweets** from neutral ones.

---

## 🧹 Data Preprocessing

Tweets are cleaned and normalized using the following steps:

- 🔹 Removal of special characters, URLs, and stopwords  
- 🔹 Tokenization and lemmatization  
- 🔹 Conversion to lowercase and general text normalization

---

## ✨ Feature Extraction

To convert the textual data into numerical features, we use three different techniques:

- 🧱 **Bag of Words (BoW)**
- 📊 **TF-IDF (Term Frequency-Inverse Document Frequency)**
- 🧠 **Word2Vec Embeddings**

Each representation captures different aspects of the tweet’s structure and meaning.

---

## 🤖 Model Building

We train **Logistic Regression models** on each of the feature sets mentioned above:

- 🔹 `BoW + Logistic Regression`  
- 🔹 `TF-IDF + Logistic Regression`  
- 🔹 `Word2Vec + Logistic Regression`

All models are implemented using **Scikit-learn** and **Gensim** libraries.

---

## 📈 Evaluation Metrics

Model performance is assessed using the following metrics:

- ✅ **F1 Score**
- 📉 **Accuracy**
- 🧮 **ROC-AUC Score**


