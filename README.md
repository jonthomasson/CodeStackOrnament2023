# CodeStack Team C 2023 Christmas Ornament Project

![Ornament Picture](pics/schematics/3d_front.png)

## Overview

Welcome to the CodeStack Team C Christmas Ornament project! This isn't just any holiday decoration; it's a geeky masterpiece designed by developers for developers. Embodying the spirit of CodeStack, this unique ornament is a playful blend of electronics and a bit of geek culture, perfect for those who appreciate the quirks of digital logic and binary systems.

### Circuit Description

Our circuit is centered around the 555 timer IC, configured in astable mode with:

- Two 12k resistors
- A 10uF capacitor

This configuration generates a 4Hz timing signal, which feeds into a CD74HC4040 binary counter. The output from this binary counter powers 12 LEDs arranged around the PCB in a binary sequence.

#### Binary Counter and LED Display

At the core of our ornament is the CD74HC4040 binary counter. Unlike traditional LED displays, this counter follows a binary sequence, lighting up LEDs in a pattern that reflects binary counting principles.

#### Reset Circuit

We've included a reset circuit using the TPS3840PH for a consistent experience. This setup ensures that the binary counter starts at zero every time the ornament is powered up. A manual reset button is also provided for added user control.

## Embracing the Geekiness

This ornament is a nod to our geeky nature at CodeStack. It's designed to intrigue and amuse, combining fundamental electronics with a bit of developer humor. It's more than just a festive decoration; it's a representation of our love for coding, circuitry, and all things geeky.

## Binary Counting Explained

This ornament is a hands-on lesson in binary counting. The binary counter ranges from 0 to 4096, with each LED representing a binary power:

- 1, 2, 4, 8, 16, 32, 64, 128, 256, 512, 1024, and 2048.

As the counter advances, the corresponding LEDs light up. To find the current count, simply add the values of all illuminated LEDs. It's a delightful way to visualize how binary numbers work!

## A Festive Joke

At first glance, it might just seem like an oddly blinking LED ornament. But in true CodeStack fashion, there's more than meets the eye. It's a playful demonstration of binary counting, making it not just a decoration, but a conversation piece about digital electronics and our geeky passions.

## Conclusion

Building and displaying this Christmas ornament is a celebration of our geeky inclinations at CodeStack. It's a testament to our love for technology, coding, and a bit of festive fun. Enjoy this unique blend of holiday cheer and geek culture!
