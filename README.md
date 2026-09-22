# CHRONOVA-BOT

CHRONOVA-BOT is a small interactive robot that I am building as a personal electronics project.

The main idea is to make a robot that can see, hear, react to movement, show information on a screen, and interact with the user through different sensors and controls.

## What it can do

The planned features include:

* TFT display for the robot's face and interface
* Joystick and buttons for controls
* RFID card and tag detection
* Microphone for voice input
* Speaker for sounds and voice output
* Camera for vision-based features
* Accelerometer for detecting movement and shaking
* Temperature and humidity sensing
* Ultrasonic distance detection
* Touch and motion detection
* Servo-controlled head movement
* Different sounds and alerts

## Main Hardware

The main controller is an ESP32-S3-WROOM-1 N16R8 development board.

Other important parts include:

* 2.8 inch 240x320 SPI TFT
* RC522 RFID reader
* INMP441 microphone
* MAX98357A amplifier
* 4 ohm 10W speaker
* ESP32-CAM
* ADXL345 accelerometer
* DHT11
* HC-SR04
* PIR sensor
* Capacitive touch sensor
* MG90S servo
* Joystick and push buttons

The complete parts list is available in [`BOM.csv`](BOM.csv).

## Power

CHRONOVA-BOT is planned to use a 3S 11.1V 2000mAh Li-ion battery.

The power system includes:

* 3S BMS
* Fuse protection
* Main power switch
* LM2596 buck converter
* 3S 12.6V charger
* Power connectors and wiring

I am keeping the power system separate from the main electronics and will test the voltage and wiring before connecting the components.

## Project Status

This project is currently being built step by step.

I am testing the individual parts first and then combining them into the final robot.

### Planned development

1. Test the ESP32-S3
2. Connect and test the TFT display
3. Add buttons and joystick
4. Test RFID
5. Add sensors
6. Add microphone and speaker
7. Add the camera
8. Add servo movement
9. Build the robot body
10. Combine everything and test CHRONOVA-BOT

## Why I am building it

I wanted to make something that combines the electronics and programming things I am learning into one actual robot.

Instead of making every feature at once, I am building and testing the robot in smaller parts and putting them together as the project progresses.

## AI Use

I used AI as a helper while working on this project, mainly for learning, debugging, and understanding components and code.

I am testing and modifying the hardware and code myself.

## BOM

The complete Bill of Materials is available here:

[BOM.csv](BOM.csv)

## Project

**Project name:** CHRONOVA-BOT
**Platform:** ESP32-S3
**Status:** In development
