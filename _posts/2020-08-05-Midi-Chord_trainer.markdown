---
layout: post
title:  "Arctic Code Vault contributor for Midi on the RapsberryPi"
date:   2020-08-05 17:56:28 +0200
categories: midi raspberrypi music
---

![Arctic Vault](../../../../../../img/vault.jpg)
###### Editorial credit: ginger_polina_bublik / Shutterstock.com


This is my first post and I didn't have anything special to share but I noticed I'm a contributor to the `Arctic Code Vault` on `Github`. Yay! Or not? Well the thing is that they chose a very personal project of mine: my midi chord trainer project. So I find it nice to share with you what it does and how it works.



[Midi chord trainer on RaspberryPi](https://youtu.be/PeY6GUZ0NfI)

<iframe width="560" height="315" src="https://www.youtube.com/embed/PeY6GUZ0NfI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Basically I wanted to memorize and practice piano chords on my midi controller keyboard and I found a way to get help from my Raspberry Pi. The Python code on the Raspberry Pi will throw at me questions about piano chords (you know the typical AbMa7 read A flat major seven) and it will handle the input notes (and other buttons pressed) to decide if my answer is correct or not. I added some options to switch the instrument, the type of chords and the way the sequence of chords is selected (random or others). Basically the typical midi stack running on Raspbian linux on the Pi will allow me to hear the notes and change the instrument. The rest is done by the Python code that leverages a deprecated library called [Mingus](https://bspaans.github.io/python-mingus/) (after the Jazz player and composer `Charles Mingus`)

![Charles Mingus Jazz player](../../../../../../img/mingus.jpg)
###### Courtesy: CSU Archives / Everett Collection. For Editorial Use Only

Is it useful? Well, I wanted to learn chords on piano and to be able to play them really fast. It turns out it is helping. But, you know, real practice is what makes you gain a skill. By playing in a sequence following the circle of fourths you can gain this skill. You can see an example 

[Tutorial from MangoldProject:](https://www.youtube.com/watch?v=inHbo-a1Rt0&list=PLoEyyUwDc_OU4MPAifF772iDBe4l_2FPY&index=16&t=20s)

<iframe width="560" height="315" src="https://www.youtube.com/embed/inHbo-a1Rt0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



Also, other great musicians suggests to use jazz standards and practice your chords there, even also learning to play the song, the chords and the melody over it or why not,  even improvising.

[Tutorial from Peter Martin:](https://www.youtube.com/watch?v=Q37PS1uW0a0)

<iframe width="560" height="315" src="https://www.youtube.com/embed/Q37PS1uW0a0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[Tutorial from Jeff Schneider:](https://www.youtube.com/watch?v=Nj90YQWaXqY)

<iframe width="560" height="315" src="https://www.youtube.com/embed/Nj90YQWaXqY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


The only thing I'm adding, besides playing with midi libraries and my midi controller, is to get random questions about chords in very different forms (triads, seventh chords, ...)
In the future I plan to add more chord types, different chord voicings, chord progressions and scales. There's plenty of room for improvement, but I hope you found it interesting at least.


![Rpi](../../../../../../img/rpimidi.jpg)



