# Keypadlock description
The following code is for a 4*4 keypad which can be used with a LCD,Ultrasonic sensor and an Arduino as a microcontroller to make a 'n' digit keypad lock with added benefits of only 3 tries and extra protection from thefts. The user has to stand at a distance of 15cm or less from the ultrasonic sensor and needs to turn the switch on for code to work. To set new password, user has to input through serial monitor.To reset circuit after 3 tries, user has to disconnect power from Arduino.The code has been made keeping power saving options in mind.

# Arduino connections - 
Keypad - dig. pins 2-6 & analog pins A0 and A2.
LCD - data pins DB4 to DB7 to dig. pins 10,9,8 & 7 || Enable to dig. pin 11 & RS to dig. pin 12.
Ultrasonic sensor - TRIG pin to analog pin A3 and ECHO pin to analog pin A4.
Servo - control pin to analog pin A1.
Slideswitch - control pin to dig. pin 13.
