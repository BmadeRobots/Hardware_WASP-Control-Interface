# WASP Control Interface

Control interface for the WASP extruder mounted to a robot.  
A LCD shows the set RPM for the extruder and if the extruder is running.

## Changing the limits
The RPM limits are set in `main.cpp` line 29-31, after changing these the program will need to be reuploaded. 
Use the following steps to reupload the program:  
  1. Open this project in Visual Studio Code
  1. Install the platformIO extension
  1. Go to the platform IO tab in the task bar on the left side of the screen
  1. Under project tasks -> Default, select build
  1. If there are no errors, switch off the control box, and plug in the usb from the control box to the computer
  1. Under project tasks -> Default, select upload

## Wiring
**TODO**: Wiring diagram

### Arduino Mega Pin Connections  

Connection | Arduino Pin 
---|---
Motor driver direction | 8
Motor driver step | 9
Motor driver Enable | 10
LCD SDA | 20
LCD SCL | 21
Push button (encoder) | 5
Encoder DT | 3
Encoder CLK | 2
Kuka IO | 13

## Wiring Diagram Reference
https://www.makerguides.com/tb6600-stepper-motor-driver-arduino-tutorial/
