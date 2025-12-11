Presenting
## The i-MAZE-ing game

A simple Maze game developed in Python, utilizing PyGame and Serial for UART communication. 

This game was built to run on a Raspberry Pi, controlled by the UART-based gaming console that our team, Team06, developed as part of our ECE 453 Capstone Project in Fall 2025. The FreeRTOS code for the console is not part of this repository.

The character is meant to be controlled by a Bluetooth-connected controller over UART, but can be modified in-code to use keystrokes instead. Debugging keystrokes have been added as part of the code, but the movement control itself was removed to reduce errors with Bluetooth control and UART commands.
