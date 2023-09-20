+++
showonlyimage = false
draft = false
image = "projects/sentimentanalysis.jpg"
date = "2022-08-02T10:16:56+01:00"
title = "Sentiment analysis classifier"
weight = 4
+++

Built an interactive widget capable of detecting sentiment using both a logistic regression model and a Naive Bayes model.
<!--more-->

> [View code on GitHub](https://github.com/jovanneste/sentimentAnalysisClassifier)

---

#### Description 
Build a CLI and GUI widget capable of understanding sentiment in natural language text. The model classifies the text as positive, neutral or negative sentiment. This project required me to train two models on a given subset of the 1.6 million sentiment tweet [dataset](https://www.kaggle.com/datasets/kazanova/sentiment140) and use the best performing one in a small GUI.

#### Logistic regression model 
A simple one-hot encoding logistic regression model applied to text features using spaCy pipline[^1]. Achieves 85% accuracy.

#### Naive Bayes model 
A more complex model based off the assumption all features are conditionally independent, which, although an oversimplification, often works well in practice for text analysis. In the context of sentiment analysis, Naive Bayes calculates the likelihood of observing certain words in positive and negative sentiments and combines this information to make sentiment predictions. Achieves 87% accuracy.


[^1]: Tokenization, part-of-speech tagging and named entity recognition.