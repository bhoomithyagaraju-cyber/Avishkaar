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

## System Components

- IV Bottle Volume Input
- Drip Rate Input
- Flow Rate Calculation Block
- Integrator Block
- Remaining Volume Calculation
- Comparator Logic
- Alert Display System

## Working Principle

1. The initial IV bottle volume is provided as input.
2. The drip rate is set as a constant.
3. Simulink calculates the fluid flow rate.
4. An integrator simulates the gradual decrease in fluid level over time.
5. The remaining fluid volume is continuously monitored.
6. Threshold values are checked using comparator blocks.
7. Alerts are generated based on the fluid level:
   - Normal Status
   - Warning Alert (below 50 mL)
   - Empty Alert (0 mL)

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
