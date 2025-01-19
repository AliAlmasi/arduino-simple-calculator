# *`Arduino Simple Calculator`*

Simple calculator built with [Arduino Uno Rev3](https://store.arduino.cc/en-de/products/arduino-uno-rev3) board

<p align=center>
  <a href='https://store.arduino.cc/cdn/shop/files/A000066_03.front_643x483.jpg'><img src='https://store.arduino.cc/cdn/shop/files/A000066_03.front_643x483.jpg' width=300></a>
  <a href='https://store.arduino.cc/cdn/shop/files/A000066_04.back_643x483.jpg'><img src='https://store.arduino.cc/cdn/shop/files/A000066_04.back_643x483.jpg' width=300></a>
  <a href='https://content.arduino.cc/assets/A000066-pinout.png'><img src='https://content.arduino.cc/assets/A000066-pinout.png' width=300></a>
</p>

## *`About this repository`*

This repository contains source code, compiled Arduino files (at the `build` directory) and necessary files for simulating the board in Proteus 8 (at the `proteus` directory).

<p align=center>
  <a href='https://raw.githubusercontent.com/AliAlmasi/arduino-simple-calculator/refs/heads/main/cal.png'><img src='./cal.png' width=500 alt='Board map schematics'></a>
</p>

## *`Dependent libraries`*

1. [LCD library (Arduino official)](https://www.arduino.cc/reference/en/libraries/liquidcrystal/)

2. [Keypad library (by Chris--A)](https://github.com/Chris--A/Keypad/)

## *`Simulate in Proteus 8`*

This project can be simulated in [Proteus 8](https://www.labcenter.com/). The whole project and the compiled source (for developing re-creating the project) is available to use in Proteus.

[Arduino Uno library for Proteus 8 (From THP website)](https://www.theengineeringprojects.com/2015/12/arduino-uno-library-proteus.html)

> [!NOTE]  
> Arduino Uno library for Proteus 8 is only required if you want to simulate the board in Proteus 8. Otherwise, it's not a dependency for board development.

> [!WARNING]  
> If you want to simulate the board in Proteus 8, be sure to choose the compiled `.hex` file (from the `build` directory) for the board in Proteus 8 enviroment. You can also compile the source code personally using the Arduino IDE.

![A screenshot from the project opened in Proteus 8 enviroment](./proteus.png)
