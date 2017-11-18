# Changing Lightbulbs

![Game prototype](https://raw.githubusercontent.com/siyant/changing-lightbulbs/master/images/game%20setup.jpeg)
![Top view of game with lights on](https://raw.githubusercontent.com/siyant/changing-lightbulbs/master/images/lights%20topview.jpeg)

A project for SUTD's 50.002 Computation Structures

## how to play
Press any of the 6 movement buttons to move around the LED cube. You can only move between lighted LEDs, and LEDs switch off once you move onto them.
Your aim is to switch off all the LEDs without getting stuck.

## game logic
The game uses a Mojo FPGA with a finite state machine for the overall logic.

![Finite state machine diagram](https://raw.githubusercontent.com/siyant/changing-lightbulbs/master/images/fsm%20diagram.png)

## components
There are 3 main hardware components (buttons, a 4x4x4 LED cube and a seven-segment display) and an arithmetic logic unit.

![Components' interactions](https://raw.githubusercontent.com/siyant/changing-lightbulbs/master/images/component%20mods.png)
