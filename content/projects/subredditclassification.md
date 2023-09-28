+++
showonlyimage = false
draft = false
image = "projects/reddit.jpeg"
date = "2021-05-23T10:16:56+01:00"
title = "Subreddit classification"
weight = 10
+++

Developed an NLP solution to automatically categorise Reddit posts into their most relevant subreddits.
<!--more-->

> [View code on GitHub](https://github.com/jovanneste/Subreddit-Classification)

---

#### Key components  
This project began with the collection of a diverse dataset of Reddit posts. These posts were extracted along with associated metadata such as dates, timestamps, and user information. I then used spaCy to tokenize the posts are represnted the posts using TF-IDF. Several models were trained on the features, including a Naive Bayes model, a linear regression model and a combined feature pipeline moded. The final model utilises a bagging approach where the models are combined and vote for classification. This improves prediction accuracy reduces overfitting. The model achieves 85% accuracy when classifying posts into one of 10 possible subreddits. 

---


