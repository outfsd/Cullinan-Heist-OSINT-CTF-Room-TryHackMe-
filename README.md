# Cullinan-Heist-OSINT-CTF-Room-TryHackMe-
A beginner-friendly OSINT challenge I designed and built, where players track a fictional thief across multiple platforms to recover stolen diamonds. Covers username enumeration, metadata analysis, git history, decoding and geolocation.

!cullinan-heist-banner.png

I'm an 17-year-old student from Switzerland and I'm in the top 2% on TryHackMe. This is the second room I built myself. 

> This writeup explains how the room was built. It contains **no answers or flags**.
> 

## The idea

The idea was to build an OSINT challenge that is beginner-friendly but fun to solve. The player's goal is to use OSINT to find out more about the thief who stole the Cullinan Diamonds and, in the end, find out in which city they are located. The only hint the players have about the thief is the username linked to him. The goal of the room is for beginners to learn and apply techniques like searching for usernames, navigating multiple websites, decoding, extracting metadata and using previously gained information to get the flags.

## How it is built

The thief is a completely made-up persona with a consistent backstory. His
footprint is spread across several places:

- **A personal blog** hosted on GitHub Pages.

!image.png

- **GitHub repositories** whose commit history reveals something
- **A Reddit profile** with a post and a comment that complete the story

## Techniques covered

The room introduces beginners to a range of core OSINT skills:

- Username enumeration across platforms
- Inspecting a website's source code
- Reading image metadata (EXIF)
- Reverse image search
- Investigating git commit history
- Recognising and decoding encoded text
- Geolocating a photo from visual clues
- Identifying and breaking a classical cipher using information found earlier

## Problems I ran into

Search engines are slow: new usernames are sometimes not indexed by Google for days, and I wanted to have the CTF ready quickly.

New Reddit accounts don't get shown in the Reddit search feature.

## Ethics

- The persona is made up.
- No real person's information is disclosed.
- Hacking or attacking any accounts or websites is prohibited and outside the scope of the room.

## What I learned

Building a room showed me the other side: creating logical paths to flags and information instead of solving, which means searching for clues and finding flags. I had a lot of fun creating this challenge, and I'm excited to see how my friends like the room.

## Playtesting & results

Before release, my brother tested the room. He got stuck at the end because of a mistake of mine in how I prepared the final step. I fixed it, and after that the room worked as intended.

## Use of AI

AI (Claude) assisted with an initial challenge outline, the blog's HTML, the graphics and hint wording. The story, questions, final challenge chain, accounts, photos and full room setup are my own work.

## Play it

 Cullinanheist OSINT

!image.png
