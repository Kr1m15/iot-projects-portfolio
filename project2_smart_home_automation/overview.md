# Project 2 – Smart Home Automation System

## Overview
Built a smart home system using Arduino microcontrollers and Home Assistant. Nodes communicated over MQTT and included real-time control of fans, RF plugs, and TVs.

## Core Features
- Centralized Home Assistant dashboard
- MQTT-driven automation
- RF socket control via 433 MHz transmitter
- IR signal relay and RS-232 TV control

## Hardware & Sensors
- Arduino MKR1000, Mega 2560, Nano
- BME680, BMP280
- RF Transmitter, IR Receiver, NRF24L01
- RS-232 module, Relay, Ethernet Shield

## System Architecture
- **Standalone Node**: Wi-Fi sensor reports to Home Assistant
- **Hub Node**: Reads sensors, transmits RF, relays IR signals
- **Linked Node**: Receives RF, controls TV over RS-232

## Skills Demonstrated
- MQTT protocol, cloud interfacing, dashboard config
- Embedded communication protocols (RF, IR, RS-232)
- Home Assistant GUI and automation flows

## Reflection
This project brought together diverse communication systems into a unified, controllable smart home network.
