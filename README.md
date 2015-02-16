# ArduinoISP-with-Serial-Debug

This is an Arduino project to give your ArduinoISP the ability to pass debug information from the Atmega on your breadboard to your computer. 

When programming an Atmega on a breadboard using an Arduino as an ISP, it can be difficult to get debug information from your breadboard to your computer. Using this file instead of the standard ArduinoISP sketch, you can program an Atmega on a breadboard and use pins 3 and 4 to send Serial debug information back to your PC. This uses the Software Serial library to create serial pins on 3 and 4 instead of using the standard 0 and 1 pins which are dedicated to interface with the computer. 

On the sketch on your breadboard chip, output serial debug at 4800 baud. (At faster speeds, I just got jumbled characters. Feel free to try faster baud rates if it works for you). Wire your breadboard chips TX to pin 3 of the Arduino ISP and RX to pin 4. 

Currently this only works for sending information from the breadboard Atmega to the PC (not the other way around). Im super busy right now but I wanted this functionality and couldnt find it anywhere so I figured somebody else might want it too. When I'm less busy I'll flesh this project out some more. If anyone wants to work on this ping me. 

This is tested on an Arduino UNO (using Atmega328P DIP) and programming an Atmega 328P. Your results may vary. 

Happy coding.
