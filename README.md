# Fake-News-Detection
A friendly model that tests and predicts whether the news is fake or real using python.

## Project Overview
Fake news spreads misinformation rapidly through online platforms. This project applies machine learning techniques to automatically detect fake news based on textual patterns. This is a beginner friendly model trained and accurated to produce results.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Google Colab

## Dataset
The dataset used in this project is sourced from Kaggle:
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

It contains labeled news articles categorized as FAKE or REAL.

## How It Works
1. Load and preprocess the dataset
2. Convert text into numerical features using TF-IDF
3. Train a Logistic Regression classifier
4. Evaluate accuracy on test data
5. Predict whether a news article is fake or real

## Output
The model predicts whether a given news article is FAKE or REAL based on learned text patterns.

## Limitations
The model relies on linguistic patterns rather than factual verification, which may lead to misclassification of some real-world news articles.

## Future Scope
- Implement deep learning models such as LSTM or BERT
- Improve text preprocessing
- Build a web interface using Streamlit
