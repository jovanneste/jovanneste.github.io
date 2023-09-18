+++
showonlyimage = true
draft = false
image = "img/portfolio/a4-paper.jpg"
date = "2022-08-02T10:16:56+01:00"
title = "Sentiment analysis classifier"
weight = 5
+++

Built an interactive widget capable of detecting sentiment. 
<!--more-->

Trains two models on a given subset of the 1.6 million sentiment tweet [dataset](https://www.kaggle.com/datasets/kazanova/sentiment140). Can then input a given sentence and see its predicted sentiment.


## Deployment

CLI deployment:
- python train_model.py (trains logistic regression and naive Bayes models)
- python evaluate_model.py (evalutes models on the some test data not used in the training)
- python predict.py (launches GUI to obtain user input)

[View code on GitHub](https://github.com/jovanneste/sentimentAnalysisClassifier)

