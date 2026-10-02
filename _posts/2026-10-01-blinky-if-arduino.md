---
layout: post
title: blinky if
subtitle: arduino assignment #2
cover-img: 
thumbnail-img: 
share-img: 
tags: [assignment, arduino, LEDs]
author: isabella
---

During this assignment, I wrote a code in the Arduino program that turns on four LED lights at varying times. When writing the program, I first defines six variables: four LEDs on the Lilypad USB, the time (n) and the wait time for each LED. In the setup code, I defined the pinModes as outputs of the four LED variables.  In the loop code, I stated that the time variable equals the time plus one second. This means that after 5 seconds, LED 5 turns on for 1 second, after 6 seconds, LED 6 turns on for 1 second., after 7 seconds, LED 7 turns on for 1 second, and after 8 seconds, LED 8 turns on for 1 second.
In order, aach LED turns on for one second and then turns off, and the next LED turns on. This loop continues infinitely. 
