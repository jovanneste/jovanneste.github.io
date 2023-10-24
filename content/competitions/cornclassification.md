+++
showonlyimage = false
draft = false
image = "projects/corn.jpg"
date = "2021-05-23T10:16:56+01:00"
title = "Corn image classification - Kaggle competition"
weight = 2
+++

Designed and implemented a CNN for a [Kaggle competition](https://www.kaggle.com/competitions/kaggle-pog-series-s01e03/overview). 
<!--more-->
---

#### Competition 
This competition (closed in 2022) involved classifing images of corn kernels into one of four distinct classes to help determine which kernels are suitable for general sale. Discoloured or broken kernels are not suitable to be sold.

#### Solution 
I built a robust deep CNN to classify images using a variety of optimisation techniques to improve accuracy. My final model leverages the Adadelta optimiser and a Keras seqentail model to extract and classify features from given images. After training, my model reaches 80& accuracy and sits in the top 8% of solutions.


> [View code on GitHub](https://github.com/jovanneste/cornImageClassification)

