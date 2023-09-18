+++
showonlyimage = false
draft = false
image = "img/portfolio/a4-paper.jpg"
date = "2023-03-24T10:16:56+01:00"
title = "Detecting and explaining emotions in video advertisements"
weight = 2
+++

This project aimed to create a framework capable of classifying emotions in advertisement videos and 

This project proposed a novel framework for detecting and explaining emotions in video advertisements. The final framework consists of two main stages: emotion detection and explanation generation. 
<!--more-->


## Deep learning model

The inital aim for this project was to create a model which, given an advertisement video, could classify the underlying emotions. This was achieved using a CNN which was trained on [Pitts dataset](https://people.cs.pitt.edu/~kovashka/ads/). More information on this model can be found [here](https://github.com/jovanneste/emotionClassificationFromVideos/tree/main/src/basicModel).


## Explainability 

To build on the classification model, I built a framework capable of explaining the decisions made by the model. Generating visual clues to give insight into model workings is becoming crucial in understanding large classification models and creating user trust. For this project, I did this by expanding a standard image model explainability framework - Local Interpretable Model-Agnostic Explanations ([LIME](https://github.com/marcotcr/lime)). My solution shows exactly which areas of specific frames our model found to be the most funny and exciting.


---

> This work was the basis of my fourth year university project.  
> [View code on GitHub](https://github.com/jovanneste/emotionClassificationFromVideos)



My framework can be run as follows:

```bash
$ python explain.py --video <> --model <> [--segments <int>] [--features <int>] [--print <bool>]
```

- `segments` : how many super pixel regions to segment our top frame into,
- `features` : how many pixel regions to show in output,
- `print` : when true, system will output step-by-step details.  

Argument descriptions can be found using "-help". For more information see this project's [README](https://github.com/jovanneste/emotionClassificationFromVideos/blob/main/README.md). The image below shows how the framework generates an output. We see here, for example, that the model found this minion falling over a chair to be the funniest part of [this video](https://www.youtube.com/watch?v=7IcGYHU8WBo).

![image](/minions.png)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#)
[![](https://img.shields.io/badge/TensorFlow-white?logo=tensorflow)](#)
[![](https://img.shields.io/badge/sk--learn-white?logo=scikit-learn)](#)
[![](https://img.shields.io/github/directory-file-count/jovanneste/emotionClassificationFromVideos)](#)