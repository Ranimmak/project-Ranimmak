# Your Project Name
PicoGame

| | |
|-|-|
|`Author` | Ranim Makhlouf

## Description
This project focuses on building a simple retro gaming console using the Raspberry Pi Pico, designed to be assembled on a board. The system demonstrates basic principles of embedded systems and programming by allowing users to create and run simple games. It can be programmed using MicroPython. The project serves as an accessible introduction to electronics and coding, using retro-style games as a practical and engaging way to develop programming skills

## Motivation
This project was chosen to combine learning programming with a fun, hands-on application, making the process more engaging and practical

## Architecture
The system architecture consists of a Raspberry Pi Pico as the central controller, connected via I2C to a 0.96-inch SSD1306 OLED display (128×64) for graphics output, multiple tactile push buttons for user input, and a 3.3V piezo buzzer for sound feedback, all assembled on a solderless breadboard using jumper (Dupont) wires to interconnect the components.

### Block diagram
<img width="1284" height="592" alt="image" src="https://github.com/user-attachments/assets/34356076-f731-490b-a8d4-c99df75fef99" />




### Schematic
Raspberry Pi Pico:
The Raspberry Pi Pico is the main controller of the system.

OLED Display:
The SSD1306 OLED display is connected to the Pico using the I2C protocol (SDA, SCL).

Push Buttons:
Push buttons are connected to GPIO pins and are used for user input.

Buzzer:
A piezo buzzer is connected to a GPIO pin to generate sound.

### Components
Raspberry Pi Pico
SSD1306 OLED Display (128x64)
Push Buttons
Piezo Buzzer
Breadboard
Jumper Wires


### Libraries
machine → GPIO, I2C, PWM

ssd1306 → OLED display

time → delays

random → game logic

## Log

<!-- write every week your progress here -->

### Week 6 - 12 May

### Week 7 - 19 May

### Week 20 - 26 May


## Reference links

<!-- Fill in with appropriate links and link titles -->

[Tutorial 1](https://www.youtube.com/watch?v=wdgULBpRoXk&t=1s&ab_channel=BenEater)

[Article 1](https://www.explainthatstuff.com/induction-motors.html)

[Link title](https://projecthub.arduino.cc/)
