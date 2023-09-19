+++
showonlyimage = false
draft = false
image = "https://www.gymlibrary.dev/_images/mountain_car.gif"
date = "2022-12-17T10:16:56+01:00"
title = "OpenAI mountain car agent"
weight = 5
+++

Built a Q-learning agent capable of completing the [mountain car game](https://www.gymlibrary.dev/environments/classic_control/mountain_car/). 
<!--more-->

#### Q-learning agent
To successfully complete this challenge, an agent must navigate the car across the hill. However, the car lacks the necessary power to ascend the hill in a single attempt. We aim to complete the task in under 1000 steps. My Q-learning agent utilises an epsilon-greedy exploration strategy to solve game. It discovers that the sole method to accomplish the task involves repeatedly traversing back and forth, gathering enough momentum to climb the hill. 

#### Double Q-learning agent
I experimented with a double Q-learning agent to improve the agent however, the gains were minimal. With more time for hyperparameter tuning and testing different explorations of strategies, this agent would have outperformed the standard agent.

> [View code on GitHub](https://github.com/jovanneste/mountainCarQLearningAgent)

![](https://www.gymlibrary.dev/_images/mountain_car.gif)

---

[![](https://img.shields.io/badge/Python-white?logo=Python)](#)

