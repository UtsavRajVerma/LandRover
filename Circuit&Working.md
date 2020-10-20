## Circuit Diagram and Working
Circuit digram for Arduino based DTMF Controlled Robot is very similar with our other robot like PC controlled robot, Line Follower, Gesture Controlled Robot, etc.. Here one motor driver is connected to arduino for driving robot. Motor driver’s input pin 2, 7, 10 and 15 is connected at arduino digital pin number 6, 5, 4 and 3 respectively. Here we have used two DC motors to driver robot in which one motor is connected at output pin of motor driver 3 and 6 and another motor is connected at 11 and 14. A 9 volt Battery is also used to power the motor driver for driving motors. A DTMF decoder attached with this circuit and this decoder is plugged into a mobile using an aux wire for receiving command or DTMF Tone. DTMF decoder pin D0-D3 is directly connected with Arduino’s pin number 19,18,17,16. Two 9 Volt batteries are used to power the circuit in which one is used for power the motors, connected at motor driver IC pin number 8. And another battery is connected to power the remaining circuit.

<p align="center">
  <img width="460" height="300" src="https://circuitdigest.com/sites/default/files/circuitdiagram_mic/Arduino-DTMF-Robot-Circuit.gif">
</p>


