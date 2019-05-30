# Voice-Controlled-Lights-Arduino
Voice Controlled Mini Home Automation Project (IOT) : Used an Arduino Uno board and Bluetooth Module. Connected LED lights to the Arduino and controlled them by using voice commands though a smartphone connected to the bluetooth module.

Can view a video of the working here https://ishita-mehta.github.io/Video-For-VoiceBt-Arduino/index.html
<br>
<br>
![](img_1.jpeg)

### Working
Arduino will be checking the incoming values all the time and controls the LEDs as per
the voice command. Arduino will turn on or off the LED according to the given Voice
command. All the received command are saved in variable “Value”
If the value is "all LED turn on" then both the LEDs turns ON, like this other voice
commands for turning on or off the individual LED is coded.
<pre>
   Command                          Action
1. all LED turn on                  Both Red and Green LED turns ON
2. turn off all devices             Both Red and Green LED turns OFF
3. turn on Red LED                  Red LED turns ON
4. turn on green LED                Green LED turns ON
5. turn off red LED                 Red LED turns OFF
6. turn off green LED               Green LED turns OFF
7. time to party                    Blinks both LED with some delay
</pre>

### COMPONENTS DESCRIPTION
1. Arduino Uno: The Arduino Uno is a microcontroller board based on the
ATmega328. It has 20 digital input/output pins (of which 6 can be used as PWM
outputs and 6 can be used as analog inputs), a 16 MHz resonator, a USB
connection, a power jack, an in-circuit system programming (ICSP) header, and a
reset button. It contains everything needed to support the microcontroller; simply
connect it to a computer (or appropriate wall power adapter) with a USB cable or
power it with a AC-to-DC adapter or battery to get started.

2. Bluetooth Module: The HC-06 is a class 2 slave Bluetooth module designed for
transparent wireless serial communication. Once it is paired to a master Bluetooth
device such as PC, smartphones and tablet, its operation becomes transparent to
the user. All data received through the serial input is immediately transmitted over
the air. When the module receives wireless data, it is sent out through the serial
interface exactly at it is received. No user code specific to the Bluetooth module is
needed at all in the user microcontroller program. The HC-06 will work with
supply voltage of 3.6VDC to 6VDC, however, the logic level of RXD pin is 3.3V
and is not 5V tolerant. A Logic Level Converter is recommended to protect the
sensor if connect it to a 5V device (e.g Arduino Uno and Mega).


