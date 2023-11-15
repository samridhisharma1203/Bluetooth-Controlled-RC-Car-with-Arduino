# Bluetooth-Controlled-RC-Car-with-Arduino
An Arduino project for a Bluetooth-controlled RC car. The code utilizes an AFMotor library to control four motors, allowing the car to move forward, backward, left, and right based on commands received through Bluetooth. The implementation ensures simplicity, ease of understanding, and optimal motor control for an enjoyable RC car experience.

# Overview
The code allows the RC car to be controlled via Bluetooth commands sent to the Arduino board. Four motors drive the car, enabling movements in four directions: forward, backward, left, and right. The implementation aims for simplicity, making it an ideal starting point for enthusiasts and beginners in Arduino projects.

# Features
__Bluetooth Control:__ Utilizes Serial communication to receive commands from a Bluetooth module, facilitating wireless control.

__Motor Control:__ Employs the AFMotor library for precise control of four motors, ensuring smooth and accurate movements.

__Directional Movement:__ Allows the RC car to move forward, backward, left, and right based on user input through a connected Bluetooth device.

# How to Use
__Hardware Setup:__ Connect the motors to the designated pins on the Arduino board and establish the Bluetooth module for communication.

__Upload Code:__ Upload the provided Arduino code to the board using the Arduino IDE.

__Bluetooth Pairing:__ Pair a Bluetooth-enabled device with the Arduino to establish a communication link.

__Control the Car:__ Send commands ('F' for forward, 'B' for backward, 'L' for left, 'R' for right) from the paired device to control the RC car.

