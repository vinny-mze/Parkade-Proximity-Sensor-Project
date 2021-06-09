How to connect opamp circuit

Introduction
● the HC SR04 Sensor outputs a signal of 5V and the maximum input signal for the
microPiHAT is 3.3V
● the opamp will be used to convert the input signal from 5V to 3.3V
● the opamp will be operating in non-inverting mode

What do you need
Here is what you will need to connect your opamp circuit:
-2 female to male jumper cable
-1 male to male jumper cable

Step 1
-Ensure that the piHat and the HC-SR04 sensor are switched off so that they won't be damaged incase thereis a short circuit

Step 2
-Use 1 female to male jumper cable to connect from pin 17 of the piHat to pin 4 of the LT1367. This is the 3.3V pin and it will be used as a refrence voltage by opamp ciruit

Step 3
-Use 1 female to male jumper cable to connect from pin 1 of the opamp to GPIO5 pin 29 of the piHat. This is the output of the opmp which goes as the input to the piHat.

Step 4
-Use 1 male to male jumper cable to connct from the HC-SR04 sensor to pin 2 of the opamp. This is the non-inverting output of the ciruit

Conclusion
-Note that all connections not mentioned in this file have already been connected

