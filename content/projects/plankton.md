+++
showonlyimage = false
draft = false
image = "img/portfolio/a4-paper.jpg"
date = "2023-04-17T10:16:56+01:00"
title = "Plankton classification"
weight = 1
+++

CNN capable of classifying images of plankton into one of 12 classes. 
<!--more-->

([dataset](https://www.dropbox.com/s/dl/v2udcnt98miwwrq/plankton.pt)). Due to class imbalances and a small dataset, I utilise data augementation and a weighted dataloader to ensure the model sees a varied and balanced representation of all classes. After training, this model achieves around 75% accuracy. I tried to improve on this by adding a self-attention mechanism to the model with limited success. 


[View code on Colab](https://colab.research.google.com/drive/1RNCGdTN7TkgZv5GmlzaXlacT2TucSDFB?usp=sharing)

[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/Jupyter-white?logo=Jupyter)](#) 
[![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#)