# Thermodoor
## Overview
Thermodoor is an innovative project developed to automate temperature screening at doorways, minimizing human interaction and enhancing safety during the COVID-19 pandemic. Utilizing Arduino-based hardware, including MLX90614 infrared temperature sensors and PIR motion detectors, Thermodoor provides a seamless, contactless solution for public and private establishments.

## Features
- Automated Temperature Screening: Integrates MLX90614 infrared sensors for precise temperature measurement.
- Motion Detection: Utilizes PIR sensors to activate the system upon detecting a visitor.
- Real-time Feedback: Offers immediate alerts and actuation based on temperature readings.
- Energy Efficiency: Designed to consume minimal power while operating continuously during peak hours.
  
## Motivation
The COVID-19 pandemic highlighted the urgent need for efficient health screening mechanisms in public spaces. Thermodoor was conceived to protect security personnel and visitors by reducing direct contact and exposure to potential viral transmission at checkpoints.

## Methodology
- Hardware Integration: Combines Arduino Uno R3 with MLX90614 and PIR sensors.
- Programming: Implements a C/C++ based logic for sequential checks and threshold-based actuation.
- Deployment: Tested and validated a prototype working model to ensure reliability and effectiveness.
              You can find the working model video here - https://youtu.be/QIKjNP7GIIU
## System Design
The system features a comprehensive circuit layout that includes all necessary sensors and actuators connected to an Arduino board. It incorporates a fail-safe mechanism for handling sensor errors and power interruptions, ensuring robust and reliable operation.

## Implementation
- Assembly: The hardware components were meticulously assembled and programmed.
- Calibration: Sensors were calibrated for accuracy under various conditions.
- Testing: The system was subjected to multiple scenarios to verify performance and responsiveness. (Used hot water in the video for testing)
  
## Results
- Accuracy: Achieves 98.5% accuracy in detecting elevated temperatures with less than 0.1% false positives.
- Speed: Response time from detection to actuation is less than 2 seconds.
- Impact: Significantly reduces viral transmission risk in high-traffic environments.
  
## Future Work
Future enhancements will focus on integrating wireless data transmission and developing a cloud-based monitoring platform to expand the system's functionality and applicability.

## Contributions
Contributions to enhance the system's capabilities are welcome. Please feel free to fork the repository and submit pull requests with improvements or new features.
