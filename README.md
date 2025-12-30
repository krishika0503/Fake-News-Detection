## Fake News Detection using Machine Learning
A beginner-friendly Natural Language Processing (NLP) project that classifies news articles as FAKE or REAL using machine learning techniques in Python.

## Author & Internship Details
Name: Krishika Agarwal
Internship Organization: Naviotech
Project Type: Internship Project
Email: krxshxka@gmail.com

This project aims to automatically detect fake news by analyzing textual patterns using machine learning, making it a practical introduction to NLP-based classification problems.

## Project Objectives
Understand text preprocessing techniques
Apply TF-IDF for feature extraction
Train a machine learning classifier
Evaluate model performance
Predict the authenticity of unseen news articles

## Technologies & Tools Used
Python – Core programming language
Pandas – Data manipulation and analysis
Scikit-learn – Machine learning algorithms
TF-IDF Vectorizer – Text feature extraction
Logistic Regression – Classification model
Google Colab – Development environment

## Dataset Description
Dataset source (Kaggle):
🔗 https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

## Dataset Features
News article text
Labels: FAKE and REAL
Large and well-balanced dataset suitable for classification tasks

## Methodology
The project follows a structured machine learning pipeline:
1)Data Loading
Import and combine fake and real news datasets
2)Text Preprocessing
Cleaning text data and removing noise
Preparing data for vectorization
3)Feature Extraction
Convert text into numerical form using TF-IDF Vectorization
4)Model Training
Train a Logistic Regression classifier on the processed data
5)Model Evaluation
Measure performance using accuracy score
6)Prediction
Classify user-input news articles as FAKE or REAL

## Results & Performance
Achieves high accuracy on test data
Performs well on general news articles
Successfully predicts authenticity of custom input text
Note: Accuracy may slightly vary due to random train-test splits.

## Sample Output
1)Input News: "Government announces new education policy..."
Prediction: REAL
2)Input News: "Celebrity claims aliens control world governments..."
Prediction: FAKE

## Limitations
Detects patterns in language, not factual correctness
May misclassify:
Satirical content
Opinion-based articles
Performance depends on dataset quality

## Future Enhancements
Implement deep learning models such as LSTM or BERT
Improve preprocessing with lemmatization and stop-word removal
Build a Streamlit-based web application
Integrate real-time news verification

## Learning Outcomes
Through this internship project, I learned:
Practical application of NLP in real-world problems
Text vectorization using TF-IDF
Building and evaluating machine learning classifiers
Complete end-to-end ML project workflow

## Conclusion
This internship project demonstrates a practical application of machine learning and NLP in tackling fake news detection.
It provides a strong foundation for beginners and can be extended into more advanced real-world systems.
