# BioBallot

## Overview

The project uses a Raspberry Pi 5 for application execution, database management, and voter authentication, while an Arduino Uno is responsible for interfacing with the hardware components such as the fingerprint sensor and LCD display. The R307 fingerprint sensor provides accurate biometric verification, ensuring secure and efficient voter authentication.

## Repository Structure

* `Arduino/` – Contains the Arduino source code for sensor interfacing and LCD control.
* `Raspberry Pi/` – Contains the Python application, database handling, and authentication logic executed on the Raspberry Pi.

## Important Note

The code provided in both the `Arduino` and `Raspberry Pi` files is designed to work only in a Raspberry Pi-based setup. The Raspberry Pi application communicates directly with the Arduino and other connected hardware components. Running these files on a standard desktop or laptop environment without the required Raspberry Pi hardware and interface will not function as intended.

## Hardware Requirements

* Raspberry Pi 5
* Arduino Uno
* R307 Fingerprint Sensor
* LCD Display
* Voter Database
* Required connecting peripherals

## Features

* Voter ID authentication
* Aadhaar-linked fingerprint verification
* Duplicate voting prevention
* Fingerprint mismatch detection
* LCD-based status display
* Raspberry Pi and Arduino serial communication

