+++
showonlyimage = false
draft = false
image = "projects/emo3.png"
date = "2023-03-24T10:16:56+01:00"
title = "Detecting and explaining emotions in video advertisements"
weight = 0
+++

This project aimed to create a model capable of detecting and explaining emotions in video advertisements. The final framework consists of two main stages: emotion detection and explanation generation. 
<!--more-->

> This work was the basis of my fourth year university project[^1].  

---

#### Deep learning classification model
The inital aim for this project was to create a model which, given an advertisement video, could classify the underlying emotions. This was achieved using a CNN which was trained on [Pitts dataset](https://people.cs.pitt.edu/~kovashka/ads/). More information on this model can be found [here](https://github.com/jovanneste/emotionClassificationFromVideos/tree/main/src/basicModel).


#### Explainability 
To build on the classification model, I built a framework capable of explaining the decisions made by the model. Generating visual clues to give insight into model workings is becoming crucial in understanding large classification models. I achieved this by expanding two standard image model explainability frameworks: Local Interpretable Model-Agnostic Explanations ([LIME](https://github.com/marcotcr/lime)), and SHapley Additive exPlanations ([SHAP](https://shap.readthedocs.io/en/latest/generated/shap.Explainer.html)). My solution shows exactly which areas of specific frames our model found to be the most funny and exciting.

---

The image below shows how the framework generates an output. We see here, for example, that the model found this minion falling over a chair to be the funniest part of [this video](https://www.youtube.com/watch?v=7IcGYHU8WBo).

![image](/minions.png)

---

[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#)
[![](https://img.shields.io/badge/TensorFlow-white?logo=tensorflow)](#)
[![](https://img.shields.io/badge/sk--learn-white?logo=scikit-learn)](#)
[![](https://img.shields.io/github/directory-file-count/jovanneste/emotionClassificationFromVideos)](#)

[^1]: This was also the basis for a research paper submitted to SIGIR 2023.