# Project 1 – Generic IoT Hub

## Overview
Developed a smart, modular IoT hub using the Arduino MKR1000 to monitor the environment. The system collected sensor readings and transmitted them via Wi-Fi to a mobile dashboard (Blynk app) and cloud database (Google Sheets).

## Core Features
- Wireless multi-sensor hub
- Monitors temperature, humidity, VOC gases, air pressure, soil moisture, and ambient light
- Motion and door detection with real-time alerts
- Mobile dashboard (Blynk) and cloud logging via Google Sheets

## Hardware & Sensors
- Arduino MKR1000
- Adafruit STEMMA Soil Sensor
- BME680 (Temp, Humidity, VOC, Pressure)
- BMP280
- PIR Motion Sensor
- Hall Effect Sensor
- TSL2591 Light Sensor
- LEDs

## Refinement & Validation
- Cross-compared BME680 and BMP280 for sensor accuracy
- Moisture smoothing with code-level averaging
- Code modularization with BlynkTimer
- Google Sheets integration via PushingBox

## Skills Demonstrated
- Embedded C/C++ with Arduino IDE
- Serial comms: I²C, SPI, 1-Wire
- Cloud API integration, soldering, debugging

## Reflection
This project strengthened my knowledge in embedded systems, cloud interfacing, and real-world prototyping.
