# Spam Message Classifier

This project implements a simple machine learning model to classify SMS messages as spam or not spam.

## Dataset
- Load dataset [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- The script uses a small inline sample dataset of SMS messages labeled as 'spam' or 'ham' (not spam).
- You can replace or extend this dataset with larger ones such as the [UCI SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection).

## Features

- Uses `CountVectorizer` to convert text messages into numerical features (bag-of-words).
- Trains a Naive Bayes classifier (`MultinomialNB`) for spam detection.

## How to Run

1. Install required libraries:

   ```bash
   pip install pandas scikit-learn
