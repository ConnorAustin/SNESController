# SNESController
My SNES died so I soldered an Arduino to the controller board portion of it.
![Image of SNES](https://raw.githubusercontent.com/ConnorAustin/SNESController/master/SnesPic.jpg)

## What is in it?
* Broken SNES
* Raspberry PI 2
* Arduino
* Electrical components (wires, breadboard, resistors, etc..)

## How does it work?
1. The Arduino communicates to the SNES controller plugged into the SNES using C.

2. The Arduino forwards the buttons presses to a Raspberry PI via USB keyboard commands.

3. The Raspberry PI is running an SNES emulator which processes the keyboard events.

4. The emulator then uses those keyboard events as inputs to the game.
