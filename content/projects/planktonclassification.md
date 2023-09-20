+++
showonlyimage = false
draft = false
image = "projects/plankton.webp"
date = "2023-04-17T10:16:56+01:00"
title = "A convolutional neural network for precise plankton classification"
weight = 6
+++

This project focused on developing a robust CNN-based solution capable of classifying images of plankton into one of 12 distinct classes. 
<!--more-->

> [View code on Colab](https://colab.research.google.com/drive/1RNCGdTN7TkgZv5GmlzaXlacT2TucSDFB?usp=sharing)

---

#### CNN
Designed and trained a deep CNN with batch normalisation and dropout using PyTorch. The final network utilises an adam optimiser and Huber loss to achieve around 80%. This task is inherently complex due to the vast variability in plankton morphology, making traditional classification methods far less effective then a deep learning solution.

#### Class imbalance problem 
This task was made more complex by large class imbalances and a small [dataset](https://www.dropbox.com/s/dl/v2udcnt98miwwrq/plankton.pt). This led to biased model predictions and reduced accuracy, as the network became overly biased toward the majority class. Addressing this challenge required innovative techniques in data preprocessing, augmentation and weighted dataloading. This ensured that the model would see a varied and balanced representation of all classes. 

#### Self-attention mechanism 
I tried to improve on my model by adding a multihead self-attention layer to the model. This network can be found [here](https://colab.research.google.com/drive/1RNCGdTN7TkgZv5GmlzaXlacT2TucSDFB?usp=sharing#scrollTo=s3MZ5Hq5iULk), although it did not improve the classification accuracy. 



---

[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) 
[![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#)