---
layout: project
title:  "UE4 Procedural Generation and Artificial Inteligence"
date:   2017-10-05 20:25:00
author: Enrique Trilles
categories:
- project
img: ue4-proc-ai.png
thumb: thumb02.jpg
tagged: C++, UnrealEngine4, Artificial Inteligence, Behavior Tree, Procedural Generation
ytbvideo: -294BvClDTE
extended: The procedural generation algorithm will build from scratch and at runtime a new maze everytime the level is loaded, making a completely different labirynth every time the game is launched. Bots have sensors for sight and hearing, and will chase the player or move to the location of the hearing sound. Although it can't be appreciated in the video, the game has music and sound effects for almost all the actions of the player. Everything music and sound related is handled with FMOD and its corresponding plugin for Unreal.

---

Project created with UnrealEngine4 v4.13. The idea for this project was to create a procedural generated maze with patrol points connected between, for several bots to travel around.
The objective of the game is to retrieve a key hidden somewhere in the maze and use it to reach the exit, while evading the patroling bots. For that purpose, the player can hide behind walls so the bots cant find him. Also, the player can crouch so the bots won't hear him while walking. With each new level, the size of the maze and the number of enemies will increase.

