---
title: Component Selection Example
---

## Examples

### Style 1

> This is the example found in the assignment, uses more html

*Table 1: Example component selection*

**External Clock Module**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image1.png)<br>Option 1.<br> XC1259TR-ND surface mount crystal<br>$1/each<br>[link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)                 | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project                                               | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.

### Style 2

**External Ultrasonic Sensor**

1. HC-SR04 Ultrasonic Sonar Distance Sensor + 2 x 10K resistors

    <img width="621" height="359" alt="image" src="https://github.com/user-attachments/assets/164d255a-cecc-442a-a3ae-f051c4a0e655" />

    * $3.95/each
    * [link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/3942/9658069)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Inexpensive                                             |                                                 |
    | Works best at 10cm to 250 cm                            |                                                 |
    | Compatible with Microcontrollers                        |                                                 |
    |                                                         |                                                 |

2. URM37 Ultrasonic Distance Sensor Breakout

<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/35cf7e42-7a4f-46ae-8cfe-90a6d35b7e8f" />


    * $13.90/each
    * [Link to product](https://www.digikey.com/en/products/detail/dfrobot/SEN0001/6588449)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    |                                                         |                                                 |
    |                                                         |                                                 |
    |                                                         |                                                 |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
