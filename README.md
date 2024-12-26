# Design and Prototyping of a Robotic Arm for Waste Sorting
This was my B-Tech Final year Capstone Project in the year 2022. <br>
This repository contains the project documentation for an innovative waste sorting system. The project aims to automate the segregation of waste into four categories: plastic, glass, paper, and metal using a 4-DOF robotic arm equipped with a vacuum gripper and computer vision-based object detection.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Design and Prototyping](#design-and-prototyping)
- [Object Detection System](#object-detection-system)
- [Control Circuit and Components](#control-circuit-and-components)
- [Future Scope](#future-scope)
- [Demonstration](#demonstration)
- [References](#references)

## Overview
Efficient waste management is critical for sustainability. This project introduces an automated waste sorting system that utilizes a robotic arm and a YOLOv7-based object detection model. The system achieves:
- Segregation of waste into four categories: plastic, paper, glass, and metal.
- Safe and efficient handling of waste, reducing manual labor and health risks.
- A classification accuracy of 70% for the trained YOLOv7 model.

## Features
- **Robotic Arm Design**: A 4-DOF robotic arm with a vacuum gripper capable of handling payloads up to 200g.
- **Object Detection**: Real-time waste classification using YOLOv7, trained on a dataset of 4878 images.
- **Control Circuit**: Integration of servo motors, an Arduino Mega 2560, and sensors for precise control and operation.
- **Prototyping**: CAD modeling and structural analysis performed to ensure reliability and durability.

## Design and Prototyping
- **Material Selection**: Stainless steel (SS304) for structural components, chosen for its strength, machinability, and corrosion resistance.
- **Manufacturing Process**: Laser cutting used for precision fabrication of robot arm components.
- **Structural Analysis**: Static and stress analysis conducted using Ansys to ensure safe operation under maximum payload conditions.

## Object Detection System
- **Model Used**: YOLOv7, a state-of-the-art object detection model, trained on a dataset of recyclable waste.
- **Performance**: Achieved an accuracy of 47% for waste classification.
- **Algorithm**: The object detection algorithm identifies and classifies waste in real-time, providing inputs for robotic arm operation.

## Control Circuit and Components
- **Microcontroller**: Arduino Mega 2560 for controlling the robotic arm and gripper mechanism.
- **Sensors**: Ultrasonic sensors for detecting object height.
- **Vacuum Gripper**: Capable of lifting both flat and irregular surfaces with a maximum payload of 500g.
- **Power Supply**: A 24V, 5A supply powers the entire system, including servo motors and vacuum pump.

## Future Scope
- **Automation**: Integration of a conveyor belt to automate waste placement and sorting without manual intervention.
- **Improved Detection**: Enhancing the object detection model's accuracy by increasing dataset size and training epochs.
- **System Integration**: Fully automating the input process by linking the camera and robotic arm for seamless operation.

## Demonstration
A demonstration video showcasing the first trial of the robotic arm and waste sorting system will be added to this repository.

## References
The project draws upon extensive research and literature, including works on robotic arm design, waste sorting systems, and object detection models. See the [documentation](https://github.com/ChinmayAmrutkar/Design_and_Prototyping_of_Robotic_Arm/blob/647a2e16e40c4f69a4f61f87151eb39a035f4cdb/Design_and_Prototyping_of_Robotic_Arm_For_Waste_Sorting_Documentation.pdf) for detailed citations.
