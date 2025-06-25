# Gesture-Controlled Robot Car

This project is a robot car that moves based on hand gestures.  
Instead of using a remote or a mobile app, we designed a glove that senses hand movement and sends signals wirelessly to the car, allowing it to move forward, backward, left, or right.

## Components Used

- 1 Arduino UNO , USB cable  
- 1 Arduino Nano , USB cable  
- 1 L298 Motor driver  
- 1 MPU6050 (accelerometer and gyroscope)  
- 2 Bluetooth modules (HC-05)  
- 5 3.7V Lithium batteries  
- 1 Battery holder for 3 batteries  
- 1 Battery holder for 2 batteries  
- 1 Car chassis with 4 DC motors and wheels  
- 1 Breadboard  
- Jumper wires (male-male and male-female)

## How It Works

The glove contains an MPU6050 sensor that detects the direction of hand movement.  
The sensor data is sent via Bluetooth to another Arduino on the car.  
The car receives the signals and uses an L298 motor driver to move accordingly.

Each gesture controls a direction:
- forward: Move forward  
- backward: Move backward  
- left or right: Turn left or right  

No physical controller is needed — only hand movement.

## Project Inspiration

We got inspired by this helpful video:  
https://youtu.be/0-n1KOc0uYk?si=YBifF_kVQTaMrOmX

## Team

Created by:  
- Noor Gafar – Electronics and Communication Engineering Student, Port Said University
-Menna Elghawy-Electronics and Communication Engineering Student, Port Said University
-Raghad Esmail-computer Engineering Student, Port Said University
