# Sentiment Analysis
The script is used to create a model to determine the sentiment of the text into negative or positive

## Dataset
https://www.kaggle.com/norptms/sentiment-analysis-by-nlp-logistic-regression/data.
Dataset contains labelled tweets as positive or negative.

## Installs
1) TensorFlow
2) sklearn
3) Matplotlib
4) Pandas
5) NLTK

## Exploratory Data Analysis
1) Checking for null values
2) Categories in target variable

## Pre-processing
1) Removing username and urls from text. 
2) Removing punctuation, stopwords and special symbols.
3) Converting categorical target variable to numerical.
4) Converting text to CountVectors 
5) Equalizing vector lengths by padding

## Model
Embedding Model: Embedding is the process of converting high-dimensional data to low-dimensional data in the form of a vector in such a way that the two are semantically similar. After that a dense network for binary classification.
