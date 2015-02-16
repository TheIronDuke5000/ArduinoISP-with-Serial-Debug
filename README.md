# ArduinoISP-with-Serial-Debug

This is an Arduino project to give your ArduinoISP the ability to pass debug information from the Atmega on your breadboard to your computer. 

When programming an Atmega on a breadboard using an Arduino as an ISP, it can be difficult to get debug information from your breadboard to your computer. Using this file instead of the standard ArduinoISP sketch, you can program an Atmega on a breadboard and use pins 3 and 4 to send Serial debug information back to your PC. This uses the Software Serial library to create serial pins on 3 and 4 instead of using the standard 0 and 1 pins which are dedicated to interface with the computer. 

