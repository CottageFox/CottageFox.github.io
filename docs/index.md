---
title: Welcome
tags:
- tag1
- tag2
---
<center>
<font size= "6">Bryce Weber Datasheet</font><br>
as part of<br>
<font size= "8"> Smart Door Sensor</font><br>
for<br>
<font size= "5"> Team 209 </font><br>

**Submission: December, 08, 2025**
</center>

## Introduction

In this datasheet I will show an overview of my subsystem for Team 209's project. It explains the functionality of my subsystem, the specific components used and how they work together, the circuitry that combines them all, and how it connects to my teammates systems. 


### Project Summary

Our project is to create a door sensor that will sense if it has been opened, then sound an alarm and lock the door. We will be using microcontrollers along with sensors, buttons, and actuators to accomplish this. My subsystem design is the sensor part which will detect if the door has been opened and output a signal to my teamates systems. The brains behind my subsystem is a Microchip PIC18F5Q43 Curiosity Nano which is a microcontroller. It can read the inputs from my sensor and then determine the distance of our system. It will then send the signal to an 8 pin ribbon cable connector that will connect to my teamates systems. The system is powered by a 9V wall power supply connected to a 5V 1.5A voltage regulator to ensure the system gets the correct power. However, this is just my part of the project, you can find the rest of our report [here.](https://asu-egr304-2025-f-209.github.io/)


### My Contribution

My part of this project is to design the sensor subsystem that will determine how far away our device is from a wall. I have an ultrasonic sensor that sends a signal to the microcontroller which then sends a signal back to the ultrasonic sensor so it can continue reading. That information can be seen through the UART function of the microcontroller's programming to see what the sensor sees and the specific values that it reads. From there I can determine how far away the device is from a wall and send that signal to my teamates systems. 

This datasheet has sections with more information on the specifics of my subsystem. <br>
For my block diagram, see [Block Diagram.](https://cottagefox.github.io/01-Block-Diagram/Block-Diagram/) <br>
For my component sellection, see [Component Selection.](https://cottagefox.github.io/02-Component-Selection/Component-Selection/) <br>
For my bill of materials, see [BOM.](https://cottagefox.github.io/03-BOM/BOM/) <br>
For my schematic, see [Schematic.](https://cottagefox.github.io/04-Schematic/schematic/) <br>
For my power budget, see [Power Budget.](https://cottagefox.github.io/05-Power-Budget/Power-Budget/) <br>
For my PCB, see [PCB Design](https://cottagefox.github.io/06-PCB-Design/06-PCB-Design/) <br>
For my code, see [Microcontroller Code](https://cottagefox.github.io/07-Microcontroller-Code/07-Microcontroller-Code/) <br>
For my Hardware V2.0, see [Hardware V2.0](https://cottagefox.github.io/08-Hardware-V2.0/08-Hardware-V2.0/) <br>
For my Resources, see [Resources](https://cottagefox.github.io/Resources/Resources/) <br>

The link to my Teams website can be found [*here*](https://asu-egr304-2025-f-209.github.io/)
