---
layout: post
title: analog arrays
subtitle: arduino assignment
cover-img: 
thumbnail-img: 
share-img: 
tags: [arduino, arrays, LEDs]
author: isabella
---

I started by defining my variables: an array with the three pwm pins on the Lilypad USB Plus arduino, Pin_Size with the number of pins in that array, and Pin_Brightness as another array with three sets of random values, one for each for each pwm pin. 
In my setup code, I define the random pin values as the output.In my loop code, I set the i variable as any random number between 0 and 3. If the pin brightness is equal to zero, or the pin is off, the pin is assigned a random value.
If the pin brightness is not equal to zero, or the pin is on, then the pin will turn off. The pin is on or off for half a second before turning off or being assigned a random value.
