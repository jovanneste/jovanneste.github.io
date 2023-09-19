+++
showonlyimage = false
draft = false
image = "img/portfolio/a4-paper.jpg"
date = "2022-05-23T10:16:56+01:00"
title = "Code Olympics 2023"
weight = 0
+++

Designed and developed reinforcement learning agents that successfully tackled multiple challenges, ultimately contributing to the overall victory of my team.
<!--more-->
--- 

#### Hackathlon 
Orginised by the University of Glasgow, the Code Olympics is a 24 hour long hackathlon where a variety of companies[^1] present challenges to be completed in groups of four. With over 50 groups in attendance, this event serves as a vibrant platform for collaboration and innovation in the world of coding and technology. 

---

#### Challenge 1: Pig dice 
This challenge involved creating an agent to play [pig](https://en.wikipedia.org/wiki/Pig_(dice_game)) with perfect strategy. At each step, the agent can roll again or stop playing - with the problem phrased like this, I developed and implemented a Q-learning agent to play the game. The agent employs an epsilon-greedy approach in order to balance its exploration of new strategies with its exploitation of known, high-reward actions. Following training against an opponent using a random strategy, my agent's Q-table revealed optimal moves for every possible position.

I improved my agent slightly by incorporating simulated annealing, a technique where the exploration of sub-optimal moves is gradually reduced over time, allowing for a more refined strategy to emerge.

My agent was tested against other people's implementations in a tournament-style game, eventually winning the competiton[^2].

> [View code on GitHub](https://github.com/jovanneste/pigDiceQLearningAgent)

---

#### Challenge 2: Jake the snake 
This challenge involved creating an agent (Jake) capable of escaping a 2D maze in the shortest amount of time with no information on its surroundings. After trialing some BFS algorithms, I devloped a Q-learning solution where, at each step, the agent can move up, down, left or right. After training, the agent can successfully navigate the maze and escape quickly. 

My agent was tested against other people's implementations in a series' of unseen mazes. With the quickest time to escape, my agent won the competition[^3].


> [View code on GitHub](https://github.com/jovanneste/escapeMazeAgents)

---

#### Awards: 
List of awards received for this hackathlon. 


##### 1st Place

- **UofG** - Pig dice
   - Explained above.
- **SAS** - Jake the snake
   - Explained above.
- **Morgan Stanley** - Genetic algorithm password solver
   - Created an agent utilising a genetic algorithm to break passwords.
- **Overall** 
   - Winners of the overall hackathlon.

##### 2nd Place

- **JPMorgan** - First person game
   - Simple POV shooter game. 


[^1]: JPMorgan, Morgan Stanley, SAS, Verint, UofG School of Computing Science.
[^2]: Challenge set by UofG School of Computing Science; £100 prize.
[^3]: Challenge set by SAS; £100 prize.