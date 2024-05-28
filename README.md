# Sentiment Analysis Using Logistic Regression

This repository contains code for sentiment analysis of sentences using Logistic Regression. The data consists of 3000 labeled sentences from reviews on various websites. The task is to classify a sentence as positive or negative based on its content.

## 1. Data Preprocessing

The code performs the following preprocessing steps on the text data:

* Removes punctuation and numbers.
* Converts all words to lowercase.
* Removes stop words (common words like "the", "a", "an").
* Converts sentences into vectors using a bag-of-words representation.

## 2. Logistic Regression Model

The code utilizes scikit-learn to train a Logistic Regression model on the preprocessed data. The model learns to classify sentences based on the presence and frequency of words.

## 3. Evaluation and Analysis

The code evaluates the model's performance on a test set and analyzes the margin of predictions. Margin refers to how confident the model is in its classification. The code investigates the relationship between margin and error rate, and explores words with a high influence on the model's predictions (positive and negative).

## 4. Files

* `SENTIMENT ANALYSIS USING LOGISTIC REGRESSION.ipynb`: Contains the main script for data loading, preprocessing, model training, evaluation, and analysis.

## 5. Dependencies

The code requires the following Python libraries:

* numpy
* matplotlib
* scikit-learn

## 6. Usage

1. Clone this repository.
2. Install the required libraries (`pip install numpy matplotlib scikit-learn`).
3. Run the script: `python SENTIMENT ANALYSIS USING LOGISTIC REGRESSION.ipynb`

This will execute the sentiment analysis pipeline and print the results including training and test errors, margin analysis, and words with high influence.
