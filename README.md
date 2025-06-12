# Counter
This repository contains a complete Proteus simulation project for a 4-bit synchronous counter

Project Overview
This repository includes simulations for:
1. Basic BCD Counter using 7447 IC
2. Digital Counter using Arduino Uno
3. 4-bit Synchronous Up/Down Binary Counter using 74192 IC

Tools & Technologies
**Proteus ISIS** (For schematic simulation)
**Arduino IDE** (for sketch in Arduino-based design)
**Digital ICs Used:**
**7447** – BCD to 7-segment display driver
**74192** – Synchronous Up/Down binary counter
**7-segment displays**
**Logic gates, clock generators, buttons**
**Microcontroller**: Arduino Uno (in simulation)

Project Details
1. BCD Counter with 7447 IC
Uses a **7490 Decade Counter** connected to a **7447 BCD to 7-segment driver**.
Displays numbers 0–9 on a common anode 7-segment display.

2. Arduino-Based Digital Counter
Programmed in Arduino IDE and simulated in Proteus.
Displays output via 7-segment or serial monitor (based on setup).
Easily customizable logic through code.

3. 4-bit Synchronous Up/Down Counter (74192)
Implements a 4-bit **up/down binary counter** using the **74192 IC**.
Up and down controls for increment/decrement.
LEDs represent binary output (00 to 99).
Synchronous operation ensures accurate toggling.
