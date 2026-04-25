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
<img width="1284" height="592" alt="image" src="https://github.com/user-attachments/assets/c9cd4fad-01c5-467f-953a-87ada9404b28" />


<!-- Make sure the path to the picture is correct -->
![Block Diagram](schematics/block_diagram.png)

### Schematic

![Schematic](schematics/kicad_schematic.png)

### Components


<!-- This is just an example, fill in with your actual components -->

| Device | Usage | Price |
|--------|--------|-------|
| Activ Buzzer | Buzzer | [1.5 RON](https://www.optimusdigital.ro/ro/audio-buzzere/635-buzzer-activ-de-3-v.html?search_query=buzzer&results=61) |
| Push Button | Button | [1 RON](https://www.optimusdigital.ro/ro/butoane-i-comutatoare/1119-buton-6x6x6.html?search_query=buton&results=222) |
| Jumper Wires | Connecting components | [7 RON](https://www.optimusdigital.ro/ro/fire-fire-mufate/884-set-fire-tata-tata-40p-10-cm.html?search_query=set+fire&results=110) |
| Breadboard | Project board | [10 RON](https://www.optimusdigital.ro/ro/prototipare-breadboard-uri/8-breadboard-830-points.html?search_query=breadboard&results=145) |

### Libraries

<!-- This is just an example, fill in the table with your actual components -->

| Library | Description | Usage |
|---------|-------------|-------|
| [lib-name1](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |
| [lib-name2](link-to-lib) | official description of the lib | Used for accesing the peripherals of the microcontroller  |

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
