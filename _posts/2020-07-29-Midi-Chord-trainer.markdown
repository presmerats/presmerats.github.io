---
layout: post
title:  "Arctic Code Vault contributor for Midi on the RapsberryPi"
date:   2020-07-29 17:56:28 +0200
categories: midi raspberrypi music
---

This is my first post and I didn't have anything special to share but I noticed I'm a contributor to the `Arctic Code Vault` on `Github`. Yay! Or not? Well the thing is that they chose a very personal project of my own: my midi chord trainer project. So I find it nice to share with you what it does and how it works.

(please imagine an image of an arctic vault with stickers of Python, NodeJS and Scala)

Basically I wanted to memorize and practice piano chords on my midi controller keyboard and I found a way to get help from my Raspberry Pi. The Python code on the Raspberry Pi will throw at me questions about piano chords (you know the typical AbMa7 read A flat major seven) and it will handle the input notes (and other buttons pressed) to decide if my answer is correct or not. I added some options to switch the instrument, the type of chords and the way the sequence of chords is selected (random or others). Basically the typical midi stack running on Raspbian linux on the Pi will allow me to hear the notes and change the instrument. The rest is done by the Python code that leverages a deprecated library called `Mingus` (after the Jazz player and composer `Charles Mingus`)

(please imagine there is a picture of charles Mingus here)

Is it useful? Well, I wanted to learn chords on piano and to be able to play them really fast. It turns out it is helping. But, you know, real practice is what makes you gain a skill. By playing in a sequence following the circle of forths you can gain this skill. You can see examples [here]() and [here](). Also, other great musicians suggests to use jazz standards and practice your chords there, even also learning to play the song, the chords and the melody over it or why not, improvising over it. See an explanation [here](). The only thing I'm adding, besides playing with midi libraries and my midi controller, is to get random questions about chords in very different forms (triads, seventh chords, ...)
In the future I plan to add more chord types, chord progressions and scales.

The whole thing is plug'n play, or kind of.. You can see a short video demo in the next link: 


[plug'n wait'n play]()
[changing between modes of working]()


Any impressions or comments are welcome! 
