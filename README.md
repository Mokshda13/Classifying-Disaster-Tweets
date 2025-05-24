
# Classifying Disaster Tweets

## Overview

This project aims to classify tweets as either disaster-related or not. Using natural language processing and machine learning techniques, the model processes a dataset of tweets to predict their relevance in disaster scenarios. It is designed to help emergency response teams filter critical information from social media in real time.

## Project Objectives

* Preprocess and clean raw tweet data
* Vectorize text using TF-IDF
* Train multiple classifiers and evaluate their performance
* Use ensemble learning to boost classification accuracy

## Dataset

The dataset consists of labeled tweets indicating whether the tweet is about a disaster. The dataset is typically in CSV format and includes:

* `id`: Unique identifier for the tweet
* `text`: The tweet content
* `target`: Binary label (1 = disaster, 0 = not disaster)

## Key Features

* Text normalization and preprocessing (stopword removal, stemming)
* TF-IDF vectorization for feature extraction
* Models: Logistic Regression, Naive Bayes, Random Forest, Support Vector Machine
* Performance evaluation using accuracy, precision, recall, and F1 score
* Confusion matrix visualization

## Dependencies

* pandas
* numpy
* sklearn
* nltk
* matplotlib
* seaborn

Install dependencies using:

```
pip install -r requirements.txt
```

## How to Run

1. Clone the repository
2. Place the dataset in the project folder
3. Run the script

```bash
python Classifying_Disaster_Tweets.py
```

## Output

* Model performance metrics printed to console
* Optional visualizations of confusion matrices
* Final ensemble model combining top-performing classifiers

## Future Improvements

* Use word embeddings such as Word2Vec or BERT for better text representation
* Deploy the model using Flask or FastAPI for real-time tweet classification
* Integrate live Twitter feed analysis using Tweepy

