---
layout: post
title: ghost detector
subtitle: arduino assignment
cover-img: 
thumbnail-img: 
share-img: 
tags: [assignment, arduino, LEDs]
author: isabella
---

Photo:

In this assignment, I programmed red LEDs to turn on when it's dark and cold. I did this by defining variables for my heat and light sensor pins and values, and then defining the led locations, one which was on the LilyPad USB board, and another which was connected using alligator clips. 
In my setup code, I defined how the sensor receives input, which is then sent to the LEDs as output. In my loop code, I tracked tempature fluctuations using celcius, and light fluctuations through a voltage variable. 

I'd recommend that anyone completing this deliverable sets a delay of 500 milliseconds in their loop code, so they can read the voltage and celcius values in the serial monitor. This allows you to observe how the voltage and celcius values fluctuate when manipulated in real time. 
 
