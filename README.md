# Naive Bayes

Implementation of Multinomial Naive Bayes from scratch using pandas and numpy. NLTK library has also been used for tokenizing and cleaning the data.

## Introduction

From [Datacamp](https://www.datacamp.com/community/tutorials/naive-bayes-scikit-learn):

Naive Bayes is a very popular statistical algorithm based on Bayes conditional probability. Naive Bayes classifier **assumes that the effect of a particular feature in a class is independent of other features**. This makes the algorithm naive, and the computation simple.

![alt text](https://www.saedsayad.com/images/Bayes_rule.png)

## Dataset 

The dataset used is taken from [Kaggle](https://www.kaggle.com/cosmos98/twitter-and-reddit-sentimental-analysis-dataset). It contains contains 37,000 comments made on Reddit along with its sentimental labelling.

A sentiment analysis has been done using Naive Bayes on the dataset to predict the correct classification.
This is the code snippet taken from the dataset:
![alt text](https://raw.githubusercontent.com/pandeyanuradha/Naive-Bayes-from-scratch-in-Python-/main/data_snippet.png)

## Workflow

Sentiment analysis is a classification problem (in this case, multiclass classification, since 3 classes).
The two files containes are:
1) Naive bayes from scratch: This jupyter notebook contains the main code for implementing Naive bayes.
2) helper.py: This python file contains helper functions( finding frequency of a particular word, cleaning the text)

We get around **60% accuracy**, which is good for a trivial model like naive bayes, since it doesn't consider the semantic relation between words.


