---
title: PalWorld Server And Issues
date: 2024-01-26 16:23:37
tags: [ game, PalWorld ]
---

Recently I'm obsessed with a game called PalWorld. It's a game that is similar to Pokémon, but with guns and more
realistic graphics.
It has a big open world, you can build your own base and craft items, fight pals(PalWorld's version of Pokémon), or you
can catch pals and let them fight for you or do some work for you.
Like other crafting games, it's always more fun to play with friends, to do so, you can start a multiplayer game and
then invite your friends to join, which can take up to 4 players.
If you want more people to join, you need to start a dedicated server. Firstly I deploy a Linux version, however, I
found it was buggy, so I switched to Windows version. My server is on the cloud, with 4 cores and 8GB RAM. It's not a
powerful server, but it's enough for a small group of people to play together.
It seems like the server program has an issue that it will crash after running for a while because of memory leak. So I
wrote a script to monitor the server and restart it when it crashes, and I open-sourced it on GitHub. 