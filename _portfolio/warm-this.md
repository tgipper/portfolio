---
layout: post
title: Warm This!
---

# Warm This! Drumming practice app

## Summary
One of the best ways to improve as a musician is to play with other musicians. A common alternative that musicians use is to play along to recordings. Warm This! is designed for drummers to warm up and practice exercises written by jazz drummer Dom Moio along with the master himself.

## Explanation
Warm This! started as an idea for a practice tool for drum students of Dom Moio. Dom has written many pages of warm ups, and he wanted to create an app that would allow students to practice along to recordings of him playing the warm ups. As a recent student of Dom’s, I offered to help build an app that students can use to play along with Dom outside of their lessons. Shortly after Dom and I had discussed creating this app, he booked some time with Tempest Recording to record himself playing all of the warm ups to be included in the app. After the recording was complete, I mixed down all of the audio files, created loops for each track, and prepared all of the sheet music to be displayed in the app.

## Problem
The goal was to create an app with sheet music that was easily readable and had simple audio playback capabilities. All of the individual warm ups are very short exercises, so the audio needed to loop seamlessly to create a more efficient warm up experience that doesn’t require the user to constantly restart the music. The last issue to solve was to find a way to monetize the app, allowing Dom to recoup the cost of creating the materials for the app.

## Solution
Creating an endlessly looping audio track proved to be a difficult challenge. As I researched ways to loop audio using JavaScript and the HTML5 audio player, I found that the built in loop function is not suitable for seamless looping. I then experimented with creating a buffer within the built-in loop function, but found that different computers need different buffer sizes. The settled on solution that was attainable with my skill set was to extend each audio file, having the content repeat multiple times within the file. This was a compromise that made it easier to build the app, but requires more storage space and requires the user to occasionally have to restart the music playback if they want the loop to extend longer.

Creating a payment system is still in the works!

## Results
The desktop version of the app is functional and easy to use. Testing with other devices such as tablets and smart phones has shown that redesign needs to be done in order for the app to be mobile friendly, which is critical since this app is most likely to be used on smartphones.

## Conclusion
Building Warm This! Presented me with multiple challenges I had not yet faced. I am disappointed that I have not yet found a way to create a seamless loop of audio, but I suspect that it can be achieved by creating a loop on the backend or by implementing this as a mobile app rather than a web-based app. I was unsure of how to achieve a seamless loop of audio at the beginning of the project, and I now have a better understanding of the difficulties of doing such precise work on the frontend of a web page.
Something I would have done differently would be to create the mobile layout first, because there are some large issues to iron out with mobile viewing of the app in it’s current state. This should have been my primary focus regarding layout because it is likely that most user will access this app on a mobile device.
In the future I will be more aware of how the majority of users are expected to use my apps. While I had a good focus on creating good functionality for the users, I did not plan to have a great user experience on the most likely used platforms.
