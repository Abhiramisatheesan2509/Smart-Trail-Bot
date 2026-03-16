# Line Follower

Line Follower is a **robot implemented on Arduino** that follows a **marked path using IR sensors**.

## Features

- Automatic line detection
- Follows a black line on a white surface
- Motor control for movement
- Real-time path correction
- Runs on Arduino

## Hardware Required

- Arduino Uno
- IR sensor module(s)
- Motor driver (L298N / L293D)
- DC motors
- Robot chassis
- Battery pack
- Jumper wires

## Libraries Used

- Arduino built-in functions

## File

- `line_follower.ino` – Main Arduino code for the line follower robot.

## How to Run

1. Connect the IR sensors and motor driver to the Arduino.
2. Assemble the robot chassis with motors and wheels.
3. Upload `line_follower.ino` using the Arduino IDE.
4. Place the robot on a track with a black line.
5. Power the robot and it will automatically follow the line.

## Circuit Diagram

![Circuit Diagram] (bot_circuit.png.jpeg)

## Demo Video
[Watch demo] (line_follower.mp4.mp4)
## Author

Abhiramisatheesan2509
