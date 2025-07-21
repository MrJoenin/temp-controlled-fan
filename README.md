# temp-controlled-fan

## Overview
This circuit uses the LM393 comparator to compare the voltage from a TMP36 temperature sensor with a user-defined threshold. When the temperature measured by the TMP36 exceeds the set threshold, a signal is sent to the NMOSFET, activating it, which in turn turns on an LED to indicate that the DC motor is running. Additionally, the LM393 will activate a buzzer if the TMP36 detects a temperature that exceeds its maximum limit. 

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

## Software Used
- Flux AI PCB
- Multisim
- ThinkerCAD

## Files
- `circuit photos` – circuit diagrams
- `PCB files` - Gerber files, BOM etc.

## Link
- https://www.tinkercad.com/things/4xYCQ1ZHnzD-smart-temperature-controlled-fan-system
