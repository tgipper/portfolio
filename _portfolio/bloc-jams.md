---
layout: post
title: Bloc Jams
---

# BlocJams

## Summary
BlocJams is a web-based music player that allows users to stream music.

## Explanation
BlocJams is designed to be a user-friendly website for listening to music. It allows users to view album art and choose the music they want to listen to from any of the hosted albums.

## Problem
The main functionality of the site is a music player, so making a simple to use interface for music playback was essential. The music player needed to be accessible as the user browses around the site, and it needed to be easy to see details about the song as it plays. The site also needs to be easy to update with new music.

## Solution
A player bar was created to stay in view at the bottom of the screen, which keeps the music player accessible no matter what else the user may be doing on the site. Playback functionality had to be accessible both on the player bar and in the main list of songs, so the AngularJS framework was used to allow playback functionality to work uninterrupted while the user navigates the site.
Using AngularJS also made it easier to update the site with new music. Templates for albums were created so that whenever an album is added to the site, it is automatically included in lists on the site and the music player can access the sound files.

## Results
The music player works great, songs can be played and paused from either the playback controls at the bottom of the page or from the list of songs. The seek bar and volume control give users more flexibility in playback as well. The site is very easy to update with new music, and the layout updates to reflect any albums that are added.

## Conclusion
This project was a great introduction to the AngularJS framework, and I learned a lot about the power of templates. The page was first built without the AngularJS framework, and then I bootstrapped Angular to the page. This allowed me to work out the functionality of the page without having to worry about learning AngularJS. Once the site was complete, it was a fairly simple process tore factor everything to work with AngularJS. What I learned from this process was that it is easier to identify and solve functionality problems first, then to fit those solutions into the UI. Because all of the functionality was solved, the process of moving to AngularJS mostly required moving sections of code around to new files that could be accessed with Angular to construct the page from templates.