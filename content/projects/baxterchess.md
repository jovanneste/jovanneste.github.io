+++
showonlyimage = false
draft = false
image = "projects/baxter.jpg"
date = "2021-12-17T10:16:56+01:00"
title = "Teaching the Baxter robot to play chess"
weight = 9
+++

Build a model leveraging computer vision and machine learning techniques to teach a robot chess.
<!--more-->

> [View code on GitHub](https://github.com/jovanneste/Chess-Baxter)

---

#### Baxter
Baxter is a two-arm robot used by University of Glasgow students for various robotics and MSc projects. It is mostly used for autonomous perception and manipulation of fabrics.

#### Playing chess

I used Python to write several scripts to teach Baxter:

- What a chessboard and its pieces look like
- The basic rules of chess
- How to pick and place a specified chess piece

All my scripts heavily utilised ROS[^1] and its node signaling capabilities. Ultimately, Baxter was able to play a game of chess against himself, albeit a very slow and tedious game.


[^1]: Robot Operating System