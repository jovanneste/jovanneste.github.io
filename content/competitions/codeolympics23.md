+++
showonlyimage = false
draft = false
image = "img/portfolio/a4-paper.jpg"
date = "2022-05-23T10:16:56+01:00"
title = "Code Olymics 2023"
weight = 0
+++

Designed and developed reinforcement learning agents that successfully tackled multiple challenges, ultimately contributing to the overall victory of my team.
<!--more-->
--- 

#### Hackathlon 

---

#### Challenge 1: Pig dice 
This challenge involved creating an agent to play [Pig](https://en.wikipedia.org/wiki/Pig_(dice_game)) with perfect strategy. At each step, the agent can roll again or stop playing - with the problem phrased like this, I developed and implemented a Q-learning agent to play the game. The agent employs an epsilon-greedy approach in order to balance its exploration of new strategies with its exploitation of known, high-reward actions. Following training against an opponent using a random strategy, my agent's Q-table revealed optimal moves for every possible position.

I improved my agent slightly by incorporating simulated annealing, a technique where the exploration of sub-optimal moves is gradually reduced over time, allowing for a more refined strategy to emerge.

My agent was tested against other people's implementations in a tournament-style game, eventually winning the competiton[^1].

> [View code on GitHub](https://github.com/jovanneste/pigDiceQLearningAgent)

---

#### Challenge 2: Jake the snake 

---

#### Awards: 

1st position for both challenges 



[![](https://img.shields.io/badge/Python-white?logo=Python)](#)
[![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#)

[^1]: Challenge set by UofG School of Computing Science.