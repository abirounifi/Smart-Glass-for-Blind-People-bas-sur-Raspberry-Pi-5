# Smart-Glass-for-Blind-People

## Overview

**Smart Glass for Blind People** is a biomedical engineering project designed to improve the mobility, safety, and independence of visually impaired people using artificial intelligence and embedded systems.

The system is built around a **Raspberry Pi 5** and integrates real-time object detection, obstacle distance measurement, and fall detection. Using the YOLOv11 object detection model and a camera, the device identifies objects in the user's surroundings. An ultrasonic sensor measures the distance to nearby obstacles, while an accelerometer detects potential falls.

The system provides audio feedback through wireless earbuds to help users become aware of nearby objects and obstacles. The project explores how computer vision and embedded AI can contribute to the development of affordable assistive technologies.

## Objectives

- Develop an intelligent assistive system to support visually impaired people in their daily mobility.
- Detect and identify surrounding objects in real time using YOLOv11.
- Measure the distance to nearby obstacles using an ultrasonic sensor.
- Detect potential falls using an accelerometer.
- Provide audio alerts to communicate detected objects and potential hazards.
- Explore the integration of artificial intelligence and embedded hardware in assistive biomedical devices.

## System Architecture

The system follows a multi-stage processing pipeline:

1. **Image Acquisition:** A camera captures images of the user's surroundings.
2. **Object Detection:** YOLOv11 processes the images to identify objects in real time.
3. **Obstacle Distance Measurement:** An HC-SR04 ultrasonic sensor measures the distance to nearby obstacles.
4. **Fall Detection:** An ADXL345 accelerometer provides motion data to identify potential falls.
5. **Audio Feedback:** Wireless earbuds deliver audio alerts to inform the user about detected objects and obstacles.
6. **Emergency Notification:** The project explores sending notifications in emergency situations, such as a detected fall.

## Technologies and Tools

- **Embedded Platform:** Raspberry Pi 5
- **Programming Language:** Python
- **Artificial Intelligence:** YOLOv11
- **Computer Vision:** OpenCV
- **Camera:** Raspberry Pi Camera
- **Ultrasonic Sensor:** HC-SR04
- **Accelerometer:** ADXL345
- **Audio Output:** Wireless earbuds
- **Domains:** Biomedical Engineering, Assistive Technology, Computer Vision, Embedded AI, and Internet of Things (IoT)

## Results

The prototype was evaluated through object detection and obstacle detection tests. The reported results are as follows:

Object Detection Performance: Approximately 22 FPS.

Obstacle Detection Accuracy: 92% for distances below 1 meter and 88% at 2 meters.

Detection Latency: Approximately 0.45 seconds at distances below 1 meter and 0.70 seconds at 2 meters.

Fall Alert Response Time: Approximately 5 seconds during testing.

These results provide an initial evaluation of the prototype's performance. Further testing under various lighting conditions and environmental scenarios is required to assess its reliability and suitability for real-world use.

The image below illustrates the physical prototype and its main hardware components.

![Smart Glass for Blind People - Physical Prototype](image/prototype.jpg)


## Limitations and Future Work

The current prototype has limitations that require further investigation, including object detection reliability in complex environments, obstacle detection coverage, and the accuracy of fall detection.

Future improvements may include:

- Improving object detection accuracy and processing speed.
- Enhancing obstacle detection in different environments.
- Reducing false fall detections.
- Improving audio feedback to make alerts more useful and accessible.
- Improving emergency notification reliability.
- Optimizing power consumption and device portability.
- Conducting more extensive tests with appropriate safety measures and user feedback.

## Disclaimer

This project is an educational biomedical engineering prototype intended to explore assistive technology for visually impaired people. It is **not a certified medical device or a replacement for a white cane, guide dog, or other established mobility aid**. The prototype has not been established as safe for independent navigation in real-world environments.

## Author

**Abir Ounifi**  
Biomedical Engineering Student  
Institut National des Technologies et des Sciences du Kef (INTeK)  
University of Jendouba, Tunisia

**Project Period:** 2025–2026
