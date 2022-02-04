---
layout: default
title: IoT Power Strip
description: 
---

## You know what but why tho? 

I recently moved into a shared apartment in New Haven, my room being in the converted attic of a beautiful old house. After I had hauled my belongings up
the three flights of stairs and my body had a chance to cool down, I sat to eat and marvel at my new abode. It was late January, and my celebratory Chipotle bowl was hot and steamy in very much the same way that my room wasn't. 

The next day I went to Walmart and bought an oil-filled electric radiator, and found that while it was perfectly capable of making my large room nice and toasty, it took about an hour to do so. I 
wished I could start the radiator remotely from my phone so that I could turn it on about an hour before I left work. This was the perfect opportunity to finally start 
that cute little smart home project that's a rite of passage for all Linux / embedded enthusiasts. 

## Design
![iot-heat-diagram](https://raw.githubusercontent.com/carlos-vaz/carlos-vaz.github.io/main/images/iot-heat.png)  

For flexibility of use in future projects, I opted to control a power switch  instead of the temperature knobs of the radiator directly. A microcontroller and stepper motor combo, powered by the power strip, would mechanically toggle the power strip switch to control the outlets, except of course the outlet that powers the controller. This means I would have to crack open ~~a cold one~~ the power strip and disconnect
the last outlet from the main rail, then connect it to the the power rails pre-switch. I would also have to paint the outlet with red or something and add a warning label "CAUTION: THIS OUTLET IS ALWAYS ON!". This of course so that I don't hurt myself when I rediscover the power strip next year in my parts bin. 

## This is so janky, why'd you use a motor instead of a relay or something?
Correct. 


