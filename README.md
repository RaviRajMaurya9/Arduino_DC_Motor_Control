# Arduino_DC_Motor_Control
control the speed of a DC motor using the L298N motor driver and displays the speed on an LCD. It provides clear wiring diagrams and well-documented code.
##### working ######
The speed of a DC motor can be controlled by varying the voltage supplied to the motor. The L298N motor driver allows for this control through Pulse Width Modulation (PWM), which is a technique where the average power delivered to the load (in this case, the motor) is controlled by turning the switch between supply and load on and off at a fast rate. By adjusting the duty cycle of the PWM signal (the proportion of time the signal is high in one cycle), the effective voltage and thus the speed of the motor can be controlled.

# Components Needed
1) Arduino Uno
2) L298N Motor Driver
3) DC Motor
4) 16x2 LCD Display
5) Breadboard and Jumper Wires
6) Power Supply (appropriate for your DC motor)

7) # L298N Motor Driver:

IN1 to Arduino digital pin 8
IN2 to Arduino digital pin 9
EN A to Arduino PWM pin 10
GND to Arduino GND
+12V to an external power supply (depending on motor voltage)
OUT1 and OUT2 to DC Motor terminals

# 16x2 LCD Display:
Liquidcrystal_I2C lcd(0x27 ,16, 2)
