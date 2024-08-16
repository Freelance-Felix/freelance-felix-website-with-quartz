---
title: Sound Manager for Godot
draft: false
tags:
  - GODOT
  - TOOL
  - ADDON
  - GDSCRIPT
  - C_SHARP
---
Sound Manager by Nathan Hoad is a tool for dealing with basic sound in Godot using object pooling. When I worked on it it already let the user play, pause and stop music or sound effects, set the audio bus to play a sfx, ui sfx or music from, set the volume and cross fade between music tracks. I added the ability to play music from a specific point in the file. It supports both GDScript and C#!

You can view the code [here](https://github.com/nathanhoad/godot_sound_manager/tree/main) or you cant download it from Godots asset library [here](https://godotengine.org/asset-library/asset/2048).

![[SoundManagerForGodotLogo.webp]]

---
# What I Did
**Programming:** I added the ability for the user to play music starting from a specific position in the file as well as still allow cross fade between music tracks. I made sure it supported GDScript and C# as well as updated the documentation to include the new functions.