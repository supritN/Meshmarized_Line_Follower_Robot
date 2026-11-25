
# Meshmarized Line Follower Robot

A high-speed autonomous line-following robot developed using Arduino Nano and a custom-built 8-channel IR sensor array. The robot detects and tracks a predefined path using real-time sensor feedback and motor control.

## Project Overview

This robot uses eight TCRT5000 infrared sensors arranged in a custom-built sensor array to detect the line and determine the robot's position relative to the track.

The Arduino Nano processes the sensor readings and controls two high-speed N20 motors through a TB6612 motor driver to make rapid steering corrections and follow the track accurately.

The robot was independently designed, assembled, programmed, and tested for competitive line-following applications.

## Components Used

| Component | Quantity |
|---|---|
| Arduino Nano | 1 |
| TCRT5000 IR Sensors | 8 |
| Custom IR Sensor Array | 1 |
| TB6612 Motor Driver | 1 |
| 500 RPM N20 Gear Motors | 2 |
| LM2596 Buck Converter | 1 |
| 3.7V Li-ion Batteries | 2 |

## Working Principle

The robot follows a predefined path using infrared light reflection.

1. The eight TCRT5000 sensors detect the difference between the line and the surrounding surface.
2. The custom IR sensor array sends digital sensor readings to the Arduino Nano.
3. The Arduino processes the sensor pattern and determines the robot's position relative to the line.
4. Based on the sensor readings, the controller adjusts the speed and direction of both motors.
5. Continuous sensor feedback allows the robot to follow the track and correct its movement.

## Software and Programming

- Programming Language: C++
- IDE: Arduino IDE
- Microcontroller: Arduino Nano
- Sensors: TCRT5000 Infrared Sensors
- Motor Driver: TB6612
- Motor Control: Dual DC Motor Control

## Features

- Custom-built 8-channel IR sensor array.
- High-speed line-following capability.
- Real-time line detection and tracking.
- Fast motor response and steering corrections.
- Compact and lightweight design.
- Rechargeable battery-powered operation.

## Achievement

**3rd Position – Mumbai Zonals, Techfest 2026, IIT Bombay**

Secured 3rd position in the Mumbai Zonals of IIT Bombay Techfest 2026 with the independently developed line-following robot.

## Project Demonstration

Video: https://youtu.be/ANjixbc1EgI

## Project Details

- Project Type: Competition Project
- Development: Independently designed, assembled, programmed, and tested.
- Achievement: 3rd Position – Mumbai Zonals, IIT Bombay Techfest 2026
- Semester: 3
- Domain: Robotics, Embedded Systems, and Autonomous Navigation

## Developer

Suprit Nandlaskar

GitHub: https://github.com/supritN

## License

This project is open-source and available for learning and educational purposes.
