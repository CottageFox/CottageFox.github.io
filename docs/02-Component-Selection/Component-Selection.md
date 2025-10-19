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

### Component Selections

**Ultrasonic Sensor**

1. HC-SR04 Ultrasonic Sonar Distance Sensor

    <img width="621" height="359" alt="image" src="https://github.com/user-attachments/assets/164d255a-cecc-442a-a3ae-f051c4a0e655" />

 * $3.95/each
 * [link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/3942/9658069)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Inexpensive                                             | Not very stable design                          |
    | Range: 10cm to 250 cm                                   | Only works with 5v                              |
    | Compatible with microcontrollers                        |                                                 |
    | Works with 5v                                           |                                                 |


2. URM37 Ultrasonic Distance Sensor Breakout

    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/35cf7e42-7a4f-46ae-8cfe-90a6d35b7e8f" />

 * $13.90/each
 * [Link to product](https://www.digikey.com/en/products/detail/dfrobot/SEN0001/6588449)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Range: 2 - 800 cm                                       | A little expensive                              |
    | Works with 5v                                           | Does not specify that it works with microcontrollers |
    | Distance can output to PWM module                       |                                                 |
    |                                                         |                                                 |


3. HRLV-ShortRange MB1604-000

    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/471e5f3a-762e-44c2-ace9-08f230bcf8ce" />

 * $34.95/each
 * [Link to product](https://www.digikey.com/en/products/detail/maxbotix-inc/MB1604-000/13422036)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Range: 1mm - 5m                                         | Expensive                                       |
    | Works with 5v                                           |                                                 |
    | Low current draw                                        |                                                 |
    |                                                         |                                                 |

   
**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.


**Op-Amp**

1. MCP6004-I/P

    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/a496aac4-5176-460e-be0d-92e7050120ce" />

 * $0.59/each
 * [link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Has 4 op-amps                                           |                                                 |
    |                                                         |                                                 |
    |                                                         |                                                 |
    |                                                         |                                                 |


2. MCP6002-I/P

    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/a496aac4-5176-460e-be0d-92e7050120ce" />

 * $0.44/each
 * [link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    |                                                         | Has 2 Op-Amps                                   |
    |                                                         |                                                 |
    |                                                         |                                                 |
    |                                                         |                                                 |


3. 

    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/a496aac4-5176-460e-be0d-92e7050120ce" />

 * $0.44/each
 * [link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    |                                                         |                                                 |
    |                                                         |                                                 |
    |                                                         |                                                 |
    |                                                         |                                                 |

