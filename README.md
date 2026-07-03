# Fake News Detection Using NLP and Machine Learning

## Project Overview

This project classifies news articles as **Fake News** or **True News** using Natural Language Processing (NLP) and Machine Learning techniques.

The project preprocesses textual news articles, converts them into numerical features using TF-IDF, and trains a Logistic Regression classifier to predict whether a news article is fake or true.


## Dataset

This project uses the **Fake and Real News Dataset** from Kaggle.

Dataset:https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

The dataset contains:
- `Fake.csv`
- `True.csv`

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Regular Expressions (re)


## NLP Preprocessing

The following preprocessing steps were performed:

- Removing special characters
- Converting text to lowercase
- Tokenization
- Stop Word Removal
- Lemmatization


## Feature Extraction

- TF-IDF Vectorization


## Machine Learning Model

- Logistic Regression


## Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report


## Project Workflow

1. Load Fake and True News datasets
2. Merge datasets
3. Label fake and true news
4. Preprocess text
5. Convert text into TF-IDF features
6. Split data into training and testing sets
7. Train Logistic Regression model
8. Predict news labels
9. Evaluate model performance
