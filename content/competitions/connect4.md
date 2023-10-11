+++
showonlyimage = false
draft = false
image = "projects/connect4.png"
date = "2021-05-23T10:16:56+01:00"
title = "Connect 4 agent - Kaggle competition"
weight = 4
+++

Built a deep reinforcement learning agent capable of playing Connect 4 for a [Kaggle competition](https://www.kaggle.com/competitions/connectx). 
<!--more-->
---

#### Competition 
The objective of the competition is to create an agent capable of playing Connect 4. Submissions are pinned against each other in a rolling leaderboard format.

#### Solution 
Using a deep Q-network and experience replay, my agent is trained with Kaggle's random and negamax agents before utilising self-play. After 10,000 games of Connect 4, my agent wins around 85% of games. For real-time updates on my agent's performance, see Kaggle's Connect X leaderboard. I experimented with curriculm learning (starting with smaller boards) in the hope of improving the agent's performence, but this had little positive impact.

> [View code on GitHub](https://github.com/jovanneste/DeepRL-Connect4)
