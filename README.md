# Spam Classifier

## Overview
This repository contains a Jupyter notebook (`spam.ipynb`) dedicated to the task of detecting spam in text messages. Utilizing various natural language processing techniques and machine learning models, this project aims to efficiently classify messages as either 'spam' or 'ham' (non-spam).

## Features
- **Data Preprocessing**: The text data undergoes a series of preprocessing steps to enhance the model's performance. This includes converting text to lowercase, removing punctuation and numbers, and stripping away common stopwords.
- **Feature Extraction**: Utilizing the `TfidfVectorizer` from scikit-learn, the project considers the term frequency-inverse document frequency of words, enriching the model's understanding of text data.
- **Model Implementation**: Instead of traditional classifiers, this project employs the Support Vector Machines (SVM) classifier for its robustness and accuracy in handling text classification tasks.
- **Performance Evaluation**: The notebook includes a thorough evaluation of the model's performance, assessing metrics such as Accuracy, Precision, Recall, F1 Score, and the Precision-Recall Curve.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: NLTK, scikit-learn, matplotlib
