+++
showonlyimage = true
draft = false
image = "projects/mondrian.webp"
date = "2022-12-08T10:16:56+01:00"
title = "Mondrian tile problem solver"
weight = 1
+++

A solution to the challenging Mondrian Tile Problem, a classic problem in computational geometry.
<!--more-->

---

#### Description 
The [Mondrian tile problem](https://mondrianpuzzle.appspot.com) consists of dissecting a square of side length n∈N into non-congruent rectangles with natural length sides such that the difference between the largest and the smallest areas of the rectangles partitioning the square is minimum[^1].

#### Solution 
My agent performs a discrete state-space search with simulated annealing to find the lowest-scoring valid solution. At each step, the agent can perform a merge or a split to one of the rectangles in order to further minimise the score. The agent is permitted to briefly navigate through invalid states, allowing quicker access to new states. It can later execute operations on these invalid states in the hope of ultimately reaching valid states with lower scores. My agent was tested on several known squares, and consistantly found optimal solutions. 

> [View code on GitHub](https://github.com/jovanneste/mondrianTilingStateSearch)

{{< embed-pdf url="./2460800v.pdf" >}}



[^1]: C. Dalfó, M.A. Fiol, N. López, 2021, Pages 64-73, ISSN 0166-218X.