# Smart IV Fluid Monitoring System

## Problem Statement

In hospitals, nurses must frequently monitor IV fluid levels for multiple patients. If an IV bottle becomes empty, it can interrupt treatment and may lead to serious complications such as blood backflow. This project automates IV fluid monitoring and alerts medical staff when the fluid level becomes low.

## Overview

The Smart IV Fluid Monitoring System is an IoT-based healthcare solution that continuously monitors the weight of an IV bottle using a load cell. When the fluid level drops below a predefined threshold, the system automatically triggers an alert through a buzzer, LED, and mobile notification.

## Features

- Real-time IV fluid level monitoring
- Automatic low-fluid alerts
- Buzzer and LED indication
- Wireless notifications using Wi-Fi
- Low-cost and easy to implement

## Hardware Components

- ESP32
- Load Cell
- HX711 Load Cell Amplifier
- Buzzer
- LED
- OLED Display (Optional)
- Breadboard
- Jumper Wires
- Power Supply

## Working Principle

1. The IV bottle is placed on the load cell.
2. The load cell continuously measures the bottle's weight.
3. The HX711 converts the analog signal into digital data.
4. ESP32 processes the readings.
5. When the weight falls below the threshold:
   - The buzzer sounds.
   - The LED turns on.
   - A notification is sent to the user.

## Applications

- Hospitals
- Clinics
- Home Healthcare
- Emergency Wards

## Advantages

- Prevents blood backflow
- Reduces manual monitoring
- Improves patient safety
- Saves nursing staff time

## Future Enhancements

- Cloud data storage
- Multiple IV bottle monitoring
- Hospital dashboard integration

## Team Members

- Mythri K N
- Bhoomika K T
- Aishwarya Naik

## License

This project is open-source and available under the MIT License.
