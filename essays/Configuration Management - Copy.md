---
layout: essay
type: essay
published: true
title: Configuration management
date: 2017-01-29
labels:
  - Software Engineering
  - Learning
---

While working on my Undertale tile puzzle game there was one consistent problem that slowed down the overall design and management of the game, and it is simply the handling of files. It was only myself and a partner working on the game for a class project however tracking the changes between files was incredibly tedious and filled with assumptions. Reflecting back, it would have been remarkably handy if some form of configuration management was used.

Keeping a synced copy of the our game without some form of version control required either a modular design or near constant communication of what code was being changed. The design of the game drifted into a design of modular parts, which enabled us to work on different parts of the game with little worry that our code would conflict or have dependency on one another. However, there were little design dependencies that had to stay consistent regargless of game's modular parts. Using sprites, music, font, and code for such had to have some form of consistency throughout the game. What transpired was a constant emailing of the game source code, trying to integrate it to the other's own progress, and emailing the code with the integration code fixes back.

What would have been useful is GitHub or any form of version control. It wasn't until later where I discovered the existence of way to track changes in a set of files and revert back. The ability to control files in such a manner is as quintessentially important as the 'undo' function (ctrl-z) and the 'redo' function (ctrl-y) found in most applications.

Back then, it did cross my mind that using github might be useful for the undertale project. I have thought that github is exclusively for large scale projects with twenty people. I did think that we would be able to do just fine without the hassle for getting acquainted with it. And we did fine without it. But using version control is apparently inevitable in software engineering.

<img class="ui left floated image" src="../images/3629643.jpg">

