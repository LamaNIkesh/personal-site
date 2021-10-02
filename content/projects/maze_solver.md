---
title: "Maze solving rover"
date: 2015-04-14
draft: false
tags: 
- C
- Arduino
- Control systems
---

### Arduino-based maze solving robot. 

This is simple wall following maze solving robot designed and put together from the scratch. The core algorithm uses PID controller as a feedback control system. There are two switch buttons that allow the user to choose which wall to follow as per the maze. Also, the robot can be manually controlled via an android app developed using MIT app inventor.

* Arduino uno powered by 9v battery.
* Two continuous servo motors driven by a 6.6 V external battery pack.
* Two Infrared sensors and one sonar sensor to sense the surroundings
* 5v voltage regulator to regulate the voltage from the 6.6 v battery pack
* RN42 bluetooth module
* Push buttons

You can view the source code [here](https://github.com/LamaNIkesh/MazeSolver-NoIntelligence) and see it in action [here](https://www.youtube.com/watch?v=fzpzEGue-wc)