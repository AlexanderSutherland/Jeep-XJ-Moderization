# Jeep XJ Modernization

This project aims to bring modern features to the Jeep Cherokee XJ, improving security, comfort, and monitoring capabilities.

## Goals

- **Upgrade Ignition System**: Implement a two-factor authentication starting system for enhanced security.
- **Device Interface**: Develop an interface to control additional devices, such as seat warmers and the electric locker.
- **Enhanced Sensor Data**: Create an interface to display additional sensor information, including:
  - Transmission temperature
  - Electric locker status (locked/unlocked)
  - Last oil change date

## Features

- **Two-Factor Start System**: Adds an extra layer of security to the ignition process.
- **Integrated Control for Accessories**: Allows control over accessories like seat warmers directly from the interface.
- **Real-Time Monitoring**: Provides live updates on critical data, such as transmission temperature and locker engagement.

## Parts
- Touch Screen: 5inch DSI Capacitive Touch Display https://www.waveshare.com/product/displays/lcd-oled/lcd-oled-1/5inch-dsi-lcd-d.htm
- MCU (Microcontrollers): STM32H747IIT6 (Basically a simple CPU)
- Synchronous Step-Down Converter: MP2338 (Use to step down 12V -> 5V or 3.3V)
- Development board: NUCLEO-F439ZI (For protyping and potentially integrate. Alternative for final product: Custom PCB Design)
- Micro SD: Samsung EVO Select microSDXC (Storage)
- BreadBoard: Elegoo Breadboard (For testing connections quickly)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/AlexanderSutherland/Jeep-XJ-Modernization.git
