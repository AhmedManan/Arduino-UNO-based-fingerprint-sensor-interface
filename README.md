# ARDUINO UNO BASED FINGERPRINT ATTENDANCE SYSTEM WITH PROTEUS SIMULATION FILE


This project demonstrates the interface between a fingerprint sensor and an Arduino Uno board. The system utilizes a 16x2 LCD to guide the user through the enrollment and scanning process. The fingerprint sensor is used for capturing and recognizing fingerprints.

## Table of Contents

- [Project Components](#project-components)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Hardware Setup](#hardware-setup)
  - [Libraries](#libraries)
- [Project Description](#project-description)
- [Circuit Diagram](#circuit-diagram)
- [YouTube Video](#youtube-video)
- [License](#license)

## Project Components

- Arduino Board Uno R3
- Finger Print Sensor (Adafruit Fingerprint Sensor)
- Liquid Crystal Display 16×2
- Connecting Wires

## Getting Started

### Prerequisites

To run the code, you will need:

- Arduino IDE installed on your computer
- Arduino Uno board
- Adafruit Fingerprint Sensor Library (link to the library)
- Proteus installed in your system (simulation purpose)

### Hardware Setup

| LCD  | Aduino Board |
|------|--------------|
| RS   | Pin 7        |
| RW   | GND          |
| E    | Pin6         |
| D4   | Pin5         |
| D5   | Pin4         |
| D6   | Pin3         |
| D7   | Pin2         |

| Fingerprint Sensor  | Aduino Board |
|------|------------|
| GND  | GND        |
| VCC  | 5V         |
| RX   | RX         |
| TX   | TX         |


### Libraries

- Adafruit Fingerprint Sensor Library
- LiquidCrystal Library

## Project Description

In this implementation of fingerprint sensor interface with Arduino Uno board. For input, I used Four push buttons. The menu on LCD guides the enrollment and scanning process. 

## Circuit Diagram

![Circuit Diagram](https://raw.githubusercontent.com/AhmedManan/Arduino-UNO-based-fingerprint-sensor-interface/9ff5467b2f5f4eb8d005a39ed648db2309ace663/fingerprint.SVG)

## YouTube Video

https://youtu.be/Pv_ZpUe7_aw

## License

You are free to use this project for personal purposes. 😇
