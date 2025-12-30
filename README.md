## Fake News Detection using Machine Learning
A beginner-friendly Natural Language Processing (NLP) project that classifies news articles as FAKE or REAL using machine learning techniques in Python.

## Author & Internship Details
Name: Krishika Agarwal
Internship Organization: Naviotech
Project Type: Internship Project
Email: krxshxka@gmail.com

This project aims to automatically detect fake news by analyzing textual patterns using machine learning, making it a practical introduction to NLP-based classification problems.

## Project Objectives
1)Understand text preprocessing techniques
2)Apply TF-IDF for feature extraction
3)Train a machine learning classifier
4)Evaluate model performance
5)Predict the authenticity of unseen news articles

## Technologies & Tools Used
1)Python – Core programming language
2)Pandas – Data manipulation and analysis
3)Scikit-learn – Machine learning algorithms
4)TF-IDF Vectorizer – Text feature extraction
5)Logistic Regression – Classification model
6)Google Colab – Development environment

## Dataset Description
Dataset source (Kaggle):
🔗 https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

## Dataset Features
1)News article text
2)Labels: FAKE and REAL
3)Large and well-balanced dataset suitable for classification tasks

## Methodology
The project follows a structured machine learning pipeline:
1)Data Loading: Import and combine fake and real news datasets
2)Text Preprocessing: Cleaning text data and removing noise and preparing data for vectorization
3)Feature Extraction: Convert text into numerical form using TF-IDF Vectorization
4)Model Training: Train a Logistic Regression classifier on the processed data
5)Model Evaluation: Measure performance using accuracy score
6)Prediction: Classify user-input news articles as FAKE or REAL

## Results & Performance
1)Achieves high accuracy on test data
2)Performs well on general news articles
3)Successfully predicts authenticity of custom input text
Note: Accuracy may slightly vary due to random train-test splits.

## Sample Output
1)Input News: "Government announces new education policy..."
Prediction: REAL
2)Input News: "Celebrity claims aliens control world governments..."
Prediction: FAKE

## Limitations
1)Detects patterns in language, not factual correctness
2)May misclassify:Satirical content and Opinion-based articles
3)Performance depends on dataset quality

## Future Enhancements
1)Implement deep learning models such as LSTM or BERT
2)Improve preprocessing with lemmatization and stop-word removal
3))Build a Streamlit-based web application
4)Integrate real-time news verification

## Learning Outcomes
1)Through this internship project, I learned:
2)Practical application of NLP in real-world problems
3)Text vectorization using TF-IDF
4)Building and evaluating machine learning classifiers
5)Complete end-to-end ML project workflow

## Conclusion
This internship project demonstrates a practical application of machine learning and NLP in tackling fake news detection.
It provides a strong foundation for beginners and can be extended into more advanced real-world systems.
