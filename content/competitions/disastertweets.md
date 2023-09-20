+++
showonlyimage = false
draft = false
image = "projects/hurricane.jpg"
date = "2021-05-23T10:16:56+01:00"
title = "Disaster tweet predictor - Kaggle competition"
weight = 2
+++

Developed and evaluated several NLP models to enter into a [Kaggle competition](https://www.kaggle.com/c/nlp-getting-started). 
<!--more-->
---

#### Competition 
The objective of the competition was to accurately categorise tweets as either related to genuine disasters or fabricated incidents. With almost 1000 entires and a rolling deadline, this is one of Kaggle's[^1] most popular competitions. 

#### Solution 
My best-performing model utilises a TF-IDF vectorised pipeline by combing together the text and location of the tweets. It then uses sklearn's Bernoulli Naive Bayes to fit the data and make prediction on unseen tweets. My model reached 80& accuracy, ranking it in the top 10% of entries. 

> [View code on GitHub](https://github.com/jovanneste/disasterTweetPredictor)

[^1]: An online platform for data science and machine learning competition.