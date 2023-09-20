+++
showonlyimage = false
draft = false
image = "projects/dyhtg.jpg"
date = "2022-05-23T10:16:56+01:00"
title = "DYHTG Hackathlon 2022"
weight = 3
+++

Competed in several challenges set by Morgan Stanley and JPMorgan. 
<!--more-->
--- 

#### Description 
Orginised by the University of Glasgow, 'Do You Have The Guts?' is a yearly hackathlon held in October. Several companies[^1] propose challenges and judge submitted solutions.

---

#### Challenge 1: Gaunlet bot
Proposed by Morgan Stanley, this challenge required teams to create an AI bot to complete in interactive Gauntlet mazes. We entered two bots into the tournament - one made to survive and escape as quickly as possible, the other made to kill other bots first then escape. I worked on the latter, developing and implementing a bot capable of travelling to desired places efficiently (using an A star algorithm) and locating other bots nearby. This bot was desinged to travel towards and shoot at other bots. 

My bot was tested against other people's implementations in a tournament-style game, where the winner of each round moved on to the next. My bot reached the final after eight rounds. 

> [View code on GitHub](https://github.com/GUTS-ms/MSGauntletBot)

---

#### Challenge 2: Weather app 
Proposed by JPMorgan, this task was to create a web-app to show weather and news headlines from offices around the world. I helped my team create a simple Django application utilising several API's to display the required information. We presented our application to a team of JPMorgan employees who awarded us first place.

> [View code on GitHub](https://github.com/GUTS-jpm/jp-connect)

---

#### Awards: 
List of awards received for this hackathlon. 

##### 1st Place
- **JPMorgan** - Weather and new web-app
   - Explained above.

##### 2nd Place
- **Morgan Stanley** - Gauntlet bot
   - Explained above. 
- **SAS** - Crack the code
   - Created a decryption algorithm to crack SAS's code. 


[^1]: JPMorgan, Morgan Stanley, Verint, GuitarGuitar, UofG School of Computing Science, SAS.