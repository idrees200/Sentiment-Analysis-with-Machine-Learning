# Sentiment Analysis with Machine Learning

This repository contains Python code for sentiment analysis using various machine learning classifiers and text vectorization techniques. The goal is to classify text sentiments (positive, negative, neutral) from a dataset using different algorithms and evaluate their performance.

## Overview

The project utilizes Python and scikit-learn to implement a sentiment analysis pipeline:

- **Data Handling**:
  - The dataset (`Q2 Sentiment Analysis Dataset.csv`) is loaded using different encodings (`utf-8`, `latin1`) to handle various text formats.
  - It is split into training and testing sets with an 80-20 split ratio for model evaluation.

- **Machine Learning Models**:
  - **Classifiers**:
    - Naive Bayes (MultinomialNB)
    - Logistic Regression
    - Random Forest
    - Support Vector Machine (SVM)
    - Perceptron

  - **Text Vectorization Techniques**:
    - Bag of Words (Raw Counts)
    - Bag of Words (TF-IDF)
    - N-grams (up to trigrams)

- **Evaluation Metrics**:
  - Models are evaluated on standard metrics:
    - Accuracy
    - Precision
    - Recall
    - F1 Score

## Setup Instructions

### Prerequisites

- Python 3.x
- pandas
- scikit-learn (sklearn)

### Installation

1. Clone the repository:

