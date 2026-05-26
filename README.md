# Ultrasonic Obstacle Detection System (Arduino)

## Project Overview:
This project is a robotics-based obstacle detection system built using Arduino UNO and multiple ultrasonic sensors. The system detects objects in real-time and provides visual and audio alerts using RGB LED and a buzzer.

This project was developed as part of structured robotics training under Automation & Coding Department (TRSKNCOE Training 2026).


## Features:
- Real-time obstacle detection using 3 ultrasonic sensors
- Direction-based distance monitoring (Front, Left, Right)
- RGB LED indication based on distance thresholds
- Buzzer alert system for safety warning
- Serial Monitor output for debugging and monitoring
- Built and simulated using Tinkercad


## Components Used:
- Arduino UNO
- Ultrasonic Sensors (HC-SR04) × 3
- RGB LED
- Buzzer
- Resistors & jumper wires
- Breadboard (Simulation)
- Tinkercad (Simulation environment)


## Working Logic
- Front sensor < 100 cm → Red LED ON  
- Right sensor < 50 cm → Green LED ON  
- Left sensor between 20–40 cm → Blue LED ON  
- Any obstacle detected → Buzzer ON  
- Otherwise system remains in idle state  


## Programming Language
- C++ (Arduino IDE)


## Learning Outcomes
- Basics of Arduino programming  
- Sensor integration (Ultrasonic sensors)  
- Conditional logic implementation in embedded systems  
- Debugging and troubleshooting C++ code  
- Real-time system behavior understanding  
- Circuit design using Tinkercad  
- Serial communication for monitoring  


## Challenges Faced
The biggest challenge was debugging the logic for multiple sensors and understanding real-time behavior in embedded systems. This was my first hands-on experience with C++ in robotics.


## Future Improvements
- Add LCD display for real-time distance output  
- Integrate IoT module (ESP32/WiFi)  
- Improve accuracy with calibration  
- Convert into physical hardware prototype

## Project Links

- GitHub Repository: https://github.com/Siddhant981/ultrasonic-obstacle-detection-system.
