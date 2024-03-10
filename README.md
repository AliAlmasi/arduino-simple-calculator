# Arduino Simple Calculator
Simple calculator built with Arduino Uno R3 board

## About this repository
This repository contains source code, compiled Arduino files (at the `build` directory) and necessary files for simulating the board in Proteus 8 (at the `proteus` directory).

![Board map](./cal.png)

## Dependent libraries
[LCD library](https://www.arduino.cc/reference/en/libraries/liquidcrystal/)  
[Keypad library](https://github.com/Chris--A/Keypad/)  
[Arduino Uno library for Proteus 8](https://www.theengineeringprojects.com/2015/12/arduino-uno-library-proteus.html)  

> Tip: If you want to simulate the board in Proteus 8, be sure to choose the compiled `.hex` file (from the `build` directory) for the board in Proteus 8 enviroment. You can also compile the source code personally using the Arduino IDE.

![A screenshot from Proteus 8 enviroment](./proteus.png)