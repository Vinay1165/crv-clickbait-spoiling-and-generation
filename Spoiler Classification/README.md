# Classifier - Milestone 2

This repository contains code for a classifier implemented in Python, including data preprocessing, feature extraction, and model training. It provides different algorithms such as Logistic Regression, Naive Bayes, Support Vector Machine (SVM), BERT, and RoBERTa for classification tasks.

## Setup

To run the code, follow these steps:

1. Install the required libraries by running the following command:

```shell
pip install transformers nltk torch tensorflow sklearn pandas numpy


2. Download the necessary data files and update the file paths in the code accordingly.

3. Run the code to train and evaluate the classifiers.

## Usage

The code is divided into the following sections:

1. **Data Preprocessing**: This section includes functions for data cleaning, tokenization, and feature extraction.

2. **Training Data Preprocessing**: This section loads the training data, selects relevant columns, and performs preprocessing steps.

3. **Generating TF-IDF**: This section generates TF-IDF (Term Frequency-Inverse Document Frequency) vectors for the clickbait and text columns.

4. **POS Tagging**: This section performs Part-of-Speech (POS) tagging on the clickbait column.

5. **Dimensionality Reduction**: This section applies dimensionality reduction techniques (Truncated SVD) to reduce the feature space.

6. **Logistic Regression Training**: This section trains a logistic regression model using the preprocessed data and evaluates its performance.

7. **Naive Bayes**: This section trains a Multinomial Naive Bayes classifier and evaluates its performance.

8. **SVM**: This section trains a Support Vector Machine (SVM) classifier and evaluates its performance.

9. **BERT**: This section fine-tunes a BERT (Bidirectional Encoder Representations from Transformers) model for sequence classification and evaluates its performance.

10. **RoBERTa**: This section fine-tunes a RoBERTa (Robustly Optimized BERT) model for sequence classification and evaluates its performance.

## Dependencies

The code requires the following libraries:

- transformers
- nltk
- torch
- tensorflow
- sklearn
- pandas
- numpy

Make sure to install them before running the code.
