---
title: Component Selection
---

### Component Selections

###**Ultrasonic Sensor**

###1. HC-SR04 Ultrasonic Sonar Distance Sensor

![Ultrasonic Image 1](https://github.com/user-attachments/assets/51443849-51f4-4ff7-a4e8-631a83d7909a)

 * $3.95/each
 * [link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/3942/9658069)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Inexpensive                                             | Not very stable design                          |
    | Range: 10cm to 250 cm                                   | Only works with 5V                              |
    | Compatible with microcontrollers                        |                                                 |
    | Works with 5V                                           |                                                 |

<br>
###2. URM37 Ultrasonic Distance Sensor Breakout

![Ultrasonic Image 2](https://github.com/user-attachments/assets/fad7b778-a96d-435b-a3d2-1818161f4941)

 * $13.90/each
 * [Link to product](https://www.digikey.com/en/products/detail/dfrobot/SEN0001/6588449)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Range: 2 - 800 cm                                       | A little expensive                              |
    | Works with 5V                                           | Does not specify that it works with microcontrollers |
    | Distance can output to PWM module                       | Weighs 25g                                      |

<br>
###3. HRLV-ShortRange MB1604-000

<img width="640" height="640" alt="Ultrasonic Image 3" src="https://github.com/user-attachments/assets/d70fd146-f869-47cf-92e6-a2755ed5f989" />

 * $34.95/each
 * [Link to product](https://www.digikey.com/en/products/detail/maxbotix-inc/MB1604-000/13422036)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Range: 1mm - 5m                                         | Expensive                                       |
    | Works with 5V                                           | Requires noise free power                       |
    | Draws 3.5mA at 5V                                       |                                                 |
    | Auto Calibration                                        |                                                 |

<br>
**Choice:** Option 1: HC-SR04 Ultrasonic Sonar Distance Sensor

**Rationale:** This is the cheapest option and the easiest to use. It has only 4 pins so it is easier to connect to the breadboard and is simple to wire so few mistakes will be made when wiring it.


###**Op-Amp**

###1. MCP6004-I/P

![OpAmp1](https://github.com/user-attachments/assets/d6c534dd-5a11-466c-a672-1b2587aed40f)

 * $0.59/each
 * [link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Has 4 op-amps                                           | Big size                                        |
    | Low Power                                               | Expensive                                       |

<br>
###2. MCP6022-I/P

![OpAmp2](https://github.com/user-attachments/assets/a153ec0e-7af1-4f1c-84d2-cd3dd0903927)

 * $0.44/each
 * [link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6022-I-P/417828)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Medium size                                             | Has 2 op-amps                                   |
    | Cheap                                                   | Power range is small                            |

<br>
###3. MCP6241-E/P

![OpAmp3](https://github.com/user-attachments/assets/3e721cca-783b-44a0-a3d5-49bb5ece966a)

 * $0.43/each
 * [link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6241-E-P/683249)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Medium size                                             | Has 1 op-amp                                    |
    | Cheap                                                   | Has 3 pins that dont connect to anything        |

<br>

**Choice:** Option 1: MCP6004-I/P

**Rationale:** This op amp has 4 op-amps which is useful when needing multiple its better to have them on the same chip instead of buying multiples. While it is the most expensive of the 3, it is very cheap.


###**Voltage Regulator**

###1. UA7805CKCS

![VoltReg2](https://github.com/user-attachments/assets/576d58b0-ad51-4f11-8c54-c000c1dc0266)

 * $1.34/each
 * [link to product](https://www.digikey.com/en/products/detail/texas-instruments/UA7805CKCS/521612)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Stable 5v output                                        | Bulky                                           |
    | Built-in thermal and short-circuit protection           | Output is not adjustable                        |

<br>

###2. L7805CV

![VoltReg3](https://github.com/user-attachments/assets/07653e4b-42fd-4726-926e-1c9006695195)

 * $0.59/each
 * [link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Wide input range                                        | Low efficiency                                  |
    | Low output noise                                        | Bulky                                           |

<br>

###3. L7805ABV

![VoltReg1fix](https://github.com/user-attachments/assets/924febb9-5292-46b2-879e-01d1fda1c330)

 * $0.59/each
 * [link to product](https://www.digikey.com/en/products/detail/stmicroelectronics/L7805ABV/634711)

    | Pros                                                    | Cons                                            |
    | ------------------------------------------------------- | ----------------------------------------------- |
    | Simple to use                                           | Low efficency                                   |
    | Built-in thermal and short-circuit protection           | Bulky                                           |
    | Low output noise                                        |                                                 |
   
<br>

**Choice:** Option 3: L7805ABV

**Rationale:** This is the simplest voltage regulator to use out of the 3. It has good protection features and low noise, making it a good option for analog circuits. 
