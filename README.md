# Obstacle Avoidance Robot (Arduino-Based)

## Overview

This project presents the design and implementation of an autonomous obstacle avoidance robot using Arduino. The system leverages ultrasonic sensing to detect obstacles and adjust its movement in real time, demonstrating practical applications of embedded systems and robotics.

## Key Features

* Real-time obstacle detection using ultrasonic sensing
* Autonomous navigation without manual control
* Directional motor control (forward, reverse, left, right, stop)
* Distance-based decision-making logic
* Simulation support using Proteus

## Technologies and Components

* Arduino (Embedded C/C++)
* Ultrasonic Sensor (HC-SR04)
* DC Motors
* Motor Driver (L298N or equivalent)
* Power Supply Module
* Proteus Design Suite

## System Operation

The robot continuously measures the distance to nearby objects using an ultrasonic sensor.

* When the path is clear, the robot moves forward
* When an obstacle is detected within a predefined threshold:

  * The robot stops
  * Selects an alternative direction (left or right)
  * Resumes movement

## Project Structure

* `newoar.ino` – Main Arduino program
* `obstacle avoidance robot.pdsprj` – Proteus simulation file
* Compiled files (`.hex`, `.bin`, `.elf`)
* Project documentation (`.docx`)

## Setup and Deployment

### Hardware

* Connect ultrasonic sensor to Arduino (VCC, GND, TRIG, ECHO)
* Interface motor driver with Arduino and DC motors
* Provide appropriate power supply

### Software

1. Open `newoar.ino` in Arduino IDE
2. Select the appropriate board and port
3. Upload the program to the Arduino

## Applications

* Basic autonomous vehicle systems
* Robotics prototyping and education
* Smart navigation systems
* Introductory industrial automation concepts

## Team Members

* Adebayo Timothy
* Adebisi Damilare
* Adegbuyi Korede
* Adediran Adeyosola
* Aseyori Abraham

## Project Value

This project demonstrates:

* Embedded systems programming
* Sensor integration and signal processing
* Real-time control logic
* Practical robotics system design

## Repository

https://github.com/KODEXJOHN123/ICT-215-GROUP-1-MECHATRONICS-DEPARTMENT
