# Overview

I have been working on a game with a few buddies of mine.  We wanted to work with networking in a fun way, so we decided to figure out online multiplayer within this context.  We are using Unity2D and the PhotonPun package to help us with the networking and server management.

I have been really focusing on animations and multiplayer combat.  I have collaborated in order to create scripts for a weapon, bullets, health, and some connecting code within the Character Controller and Player Movement scripts.  Everything that I worked on these past few weeks has been focused around getting the multiplayer to interact with each of these scripts correctly.


[Software Demo Video](https://youtu.be/O28Q-4tQsBQ)

# Development Environment

My team and I have been using Unity2D as our interface of choice. Within that, I have been focused on using the built in animations/animator functionalities. The animator allows us to visually script many if-else statements. Unity uses C# as its language of choice, so I have been getting some good practice with using Object Oriented programming. We have been using various packages, but mainly just Photon. We have been using PhotonPun to add multiplayer functionality into our game. 

# Useful Websites

{Make a list of websites that you found helpful in this project}

- [ChatGPT](https://chat.openai.com/)
- [2D Shooting Tutorial - Youtube](https://www.youtube.com/watch?v=wkKsl1Mfp5M&t=654s)

# Future Work

- We still have some issues with some animations looping incorrectly.
- We need to somehow sync death animations across the server, since sometimes characters won't get destroyed when they are supposed to.
- Flipping character sprites results in an unintended paper-like flip, but we may keep it