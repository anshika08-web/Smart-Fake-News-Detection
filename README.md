# Smart-Fake-News-Detection
Project Overview

The Smart Fake News Detection System is a Machine Learning-based project designed to classify news articles as REAL or FAKE using Natural Language Processing (NLP) techniques.

The system analyses the textual content of news articles and uses trained machine learning algorithms to predict their likely category.

Objectives

To understand and implement Machine Learning concepts.

To preprocess and clean textual news data.

To convert text into numerical features using TF-IDF.

To train and compare different classification algorithms.

To evaluate model performance using standard evaluation metrics.

To build a simple system that accepts news text and generates predictions.

Dataset Information

Dataset: Fake and Real News Dataset

Total original records: 4,594

Columns: idd, title, text, label

Target categories: REAL and FAKE

The dataset was cleaned by removing missing values and duplicate records.

Technologies Used

Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

NLTK / Regular Expressions

Joblib

Machine Learning Algorithms

The project implements and compares:

Logistic Regression

Multinomial Naive Bayes

Methodology

Dataset collection and loading

Data inspection and cleaning

Text preprocessing

Feature and target selection

Train-test splitting (80:20)

TF-IDF Vectorization

Model training

Model evaluation

Confusion matrix and classification report

News prediction

Evaluation Metrics

The models are evaluated using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

Project Files

fake_news_model.pkl – Trained machine learning model

tfidf_vectorizer.pkl – Saved TF-IDF vectorizer

model_evaluation_results.csv – Model comparison results

cleaned_news_dataset.csv – Processed dataset

How to Run the Project

Download or clone this repository.

Open the Jupyter Notebook in Google Colab.

Install the required Python libraries.

Load the dataset.

Run the notebook cells in sequence.

Enter a news headline or article to obtain a prediction.

Future Scope

Integrating a larger and more diverse news dataset.

Exploring advanced NLP and deep learning techniques.

Developing a user-friendly web application.

Improving generalisation to new and unseen news sources.

Important Note

This project is an educational machine learning prototype. Its predictions are based on patterns learned from the training dataset and should not be treated as independent verification of whether a news story is true.

Author

Student Machine Learning Project

Project: Smart Fake News Detection System
