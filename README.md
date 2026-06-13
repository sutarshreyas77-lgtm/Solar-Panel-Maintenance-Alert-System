# Solar Panel Maintenance Alert System

## Overview
The Solar Panel Maintenance Alert System is an IoT-based solution designed to monitor solar panel performance and notify users when maintenance is required.

The system continuously measures panel output voltage using a voltage sensor connected to an ESP8266 NodeMCU. When voltage drops below a predefined threshold due to dust accumulation, shading, or panel faults, the system sends maintenance alerts through the Blynk IoT platform.

## Features
- Real-time voltage monitoring
- Wi-Fi enabled remote access
- Mobile notifications using Blynk
- Fault detection based on threshold values
- Live dashboard visualization
- Low-cost implementation

## Hardware Used
- ESP8266 NodeMCU
- Voltage Sensor Module
- IRLZ44N MOSFET
- Solar Panel
- Power Supply

## Software Used
- Arduino IDE
- Blynk IoT Platform
- Embedded C/C++

## System Block Diagram

(Add image here)

## Circuit Diagram

(Add image here)

## Working Principle

1. Solar panel output voltage is measured continuously.
2. ESP8266 processes voltage data.
3. Voltage threshold is compared with actual readings.
4. If voltage falls below threshold:
   - Fault detected
   - Maintenance alert generated
5. Data is uploaded to Blynk cloud.
6. User monitors system remotely via smartphone.

## Results

- Successful real-time monitoring
- Instant maintenance notifications
- Reduced manual inspection effort
- Improved solar panel efficiency

## Future Improvements

- Machine Learning based fault prediction
- Current and power monitoring
- Multiple panel support
- Web dashboard integration

## Author

Shreyas Sutar
Electronics & Telecommunication Engineering
