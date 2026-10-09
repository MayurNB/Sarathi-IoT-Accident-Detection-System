# Sarathi — IoT-Based Accident Detection and Emergency Response System

## Overview

Sarathi is a final-year academic group project that explored the concept of an IoT-based road-accident detection and emergency-response system.

The proposed idea was to combine vehicle sensors, location information, communication services and a web interface to support the reporting of possible road accidents.

**Project type:** Academic group project
**My primary focus:** System concept, problem analysis and web-side development attempts
**Project status:** Partial prototype; complete end-to-end functionality was not achieved

## Problem Statement

When a road accident occurs, communicating the incident and its location quickly can be important. Sarathi explored a system concept intended to detect a possible accident and communicate relevant information to emergency contacts.

## Proposed System Architecture

The report describes three main areas:

1. **Hardware-based accident detection:** An ESP32-based controller and sensors intended to identify possible accident-related events.
2. **Notification module:** A proposed Telegram integration intended to send accident-related messages.
3. **Web-based interface:** A proposed interface for presenting accident-related information.

These describe the intended design, not proof that the complete system worked.

## Conceptual Workflow

1. Sensors are intended to provide vehicle-motion or vibration information.
2. The controller is intended to process sensor information.
3. GPS is intended to provide location coordinates.
4. The system is intended to pass accident-related information to notification or web modules.

The complete workflow was not successfully implemented and verified end to end.

## My Contribution

My main focus was the project concept, understanding the problem, and considering how the hardware and software components could fit together.

My contributions included project documentation and diagrams, arranging hardware components, participating in hardware-related attempts, and attempting to develop parts of the web-side prototype using Core PHP and Bootstrap.

I did not independently implement the complete hardware system or all software modules. Other project activities and modules were handled collaboratively by group members.

## Technologies and Components

### Web-side development

* Core PHP and Bootstrap — used or attempted for parts of the web prototype.

### Proposed hardware

* ESP32 microcontroller
* MPU6050 accelerometer/gyroscope
* SW-420 vibration sensor
* NEO-6M GPS module

### Proposed communication

* Telegram Bot API

The proposed components and technologies above do not imply that every component was integrated successfully. My personal coding contribution to the hardware and notification modules was limited.

## Implementation Status

* **System concept and architecture:** Developed as part of the academic project.
* **Web interface:** Partial development attempts; the website was not fully functional.
* **Telegram integration:** Not successfully completed.
* **Hardware-related implementation:** Partial work; I cannot claim that the complete accident-detection workflow worked reliably.
* **End-to-end integration:** Not achieved as a fully functional system.

See [`docs/implementation-status.md`](docs/implementation-status.md) for more detail.

## Challenges and Learning

The project helped me understand the difference between designing a system and implementing a working solution. It highlighted the importance of verifying individual modules, debugging hardware–software communication, testing integrations, and documenting implementation limitations accurately.

## Future Improvements

Potential future improvements include:

* Completing and testing the web application.
* Verifying sensor readings and accident-detection logic.
* Establishing and testing communication between hardware and software modules.
* Implementing and verifying the notification workflow.
* Performing integration and reliability testing.

These are future improvements, not completed features.

## Project Documentation

This repository provides a concise overview of the project concept, my contribution and the implementation status. The full academic report is maintained separately and can be provided when legitimately required.

## Academic Project

Sarathi was developed as a group project. Contributions varied among team members. This description focuses on my own involvement and distinguishes proposed functionality from verified implementation.
