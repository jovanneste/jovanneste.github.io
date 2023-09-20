+++
showonlyimage = false
draft = false
image = "projects/mcmc7.png"
date = "2021-05-23T10:16:56+01:00"
title = "Natural language decryption using MCMC"
weight = 2
+++

Using an advanced Markov Chain Monte Carlo sampling algorithm, I built an agent capable of decrypting encrypted texts. 
<!--more-->

> [View code on GitHub](https://github.com/jovanneste/MCMCDecrypter)

---

#### Description 
This project aimed to create an decrypter capable of iteratively decrypting text encrypted by a random mapping.

#### MCMC solution  
The decrypter initally constructs a 2D probability grid based on bi-grams from a large corpus of English text. From here, we have the ability to give input text a score of based on how likely the text is made up of Emglish. We use MCMC sampling to allow the decrypter to explore a vast space of possible text transformations, iteratively improving the decryption process.

Usually, after around 100,000 iterations, the decrypter will reach a minimum which is hopefully the same text (or a very close approximation) of the orignal text.

---

[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
