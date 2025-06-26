
# 🚨 Sentiment Analysis of Tweets for Hate Speech Detection

This project aims to classify tweets based on whether they contain hate speech, specifically racist or sexist content. It is framed as a binary classification task.

📌 Objective
Given a dataset of tweets labeled as either hateful (1) or not hateful (0), the objective is to build models that can accurately identify racist or sexist tweets from normal ones.

🧹 Data Preprocessing
Tweets are preprocessed by:

Removing special characters, URLs, stopwords

Tokenization and lemmatization

Lowercasing and normalization

✨ Feature Extraction
To convert the textual data into numerical features, we use:

🧱 Bag of Words (BoW)

📊 TF-IDF (Term Frequency-Inverse Document Frequency)

🧠 Word2Vec Embeddings

Each representation captures different aspects of the language used in tweets.

🤖 Model Building
We train Logistic Regression models using each of the three feature sets:

BoW + Logistic Regression

TF-IDF + Logistic Regression

Word2Vec + Logistic Regression

All models are built using Scikit-learn and Gensim.

📈 Evaluation Metrics
Model performance is measured using:

✅ F1 Score

📉 Accuracy

🧮 ROC-AUC Score
