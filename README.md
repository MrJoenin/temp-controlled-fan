# temp-controlled-fan
Analogue Circuit that instruct a DC motor fan to turn on base on the temperature reading from the tmp36. A buzzer is included to indicate temperature threshold limit exceeded.

## Overview
This circuit uses lm393 to compare voltages between the threshold and the tmp36. If the tmp36 exceeds the threshold temperature set by the user, a signal is sent to the nmosfet to activate and LED is turned on indicate the dc motor is moving. The lm393 activates a buzzer when tmp36 temperature exceeds its maximum temperature. 

## Features
- Duel Comparator (lm393) x1
- Zener Diode x1
- Temperature Sensor (tmp36) x1
- Buzzer x1
- LED x1
- DC Motor x1
- N Mosfet x1
- Resistors x8
- Potentiometer x1
- NPN transistor x1
- Switch button x1

## Files
- `circuit photos` – circuit diagram
- `arm_control.ino` – Arduino sketch
- `solidworks/` – CAD files
- `images/` – Build photos

## Author
John Yalley – ECET student at NJIT
