---
title: Achromatic
draft: false
tags:
  - UNITY
  - UNITY_3D
  - GAME
  - C_SHARP
  - PC
---
Achromatic is a 3D horror game where the player has to navigate an abandoned 1950s inspired carnival. This game was for my Capstone class and we were a team of 16 people (4 programmers). I was in charge of tools, AI and storyboarded/edited the trailer and team intro videos.

You can find the steam page [here](https://store.steampowered.com/app/1990210/Achromatic/), the trailer [here](https://www.youtube.com/watch?v=j-wnhaJXZI4) and the team intro [here](https://www.youtube.com/watch?v=AlQz73QMAU0).

![[AchromaticSplash.webp]]

---
# What I Did
**Tools Programming:** I developed a QA tool for my team to use at testing to help get more accurate player data. It uses an FOV Tool I made to detect when the player is looking at something and it’ll record how long the player looked at an object. It also records the players location every X seconds. It takes all this data and exports it to a CSV, which the designers can then open up in google sheets to get more accurate data on where the player spent the most time, items/areas they missed etc. They can also import the player movement data and replay where the player went to throughout the game.

**AI Programming:** I programmed in the AI for the mannequins. Using the FOV Tool along with a behavior tree plug-in, I put together an AI where the mannequin will chase the player when the player isn’t looking at them and stop when they are. The mannequin plays an animation and pauses their animation when the player is looking at them.

![[AchromaticFOVTool.gif]]