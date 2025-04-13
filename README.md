# Product Review Sentiment Analysis

This project focuses on analyzing the sentiment (Positive, Negative, and Neutral) of various product reviews using machine learning models and different text embedding techniques.

## 📌 Features
- Implemented multiple text embeddings: **Bag of Words (BoW), TF-IDF, Word2Vec, and GloVe**.
- Built sentiment classifiers using **Random Forest**.
- Trained on both balanced and unbalanced datasets.
- Performed hyperparameter tuning to improve accuracy.

## 📊 Model Performance

| Model Variant                      | Train Accuracy | Test Accuracy |
|-----------------------------------|----------------|---------------|
| Random Forest (BoW)               | 1.000000       | 0.841584      |
| Random Forest (TF-IDF)            | 1.000000       | 0.821782      |
| Random Forest (Word2Vec)          | 1.000000       | 0.841584      |
| Random Forest (GloVe)             | 0.997512       | 0.841584      |
| Random Forest (BoW, Balanced)     | 1.000000       | 0.841584      |
| Random Forest (TF-IDF, Balanced)  | 1.000000       | 0.841584      |
| Random Forest (Word2Vec, Balanced)| 1.000000       | 0.841584      |
| Random Forest (GloVe, Balanced)   | 0.997512       | 0.841584      |
| Random Forest (BoW, Tuned)        | 0.865672       | 0.821782      |
| Random Forest (TF-IDF, Tuned)     | 0.899254       | 0.831683      |
| Random Forest (Word2Vec, Tuned)   | 0.896766       | 0.821782      |
| Random Forest (GloVe, Tuned)      | 0.997512       | 0.841584      |

