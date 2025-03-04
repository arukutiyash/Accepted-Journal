# Accepted-Journal
# Drowsiness Detection System

## Overview
The **Drowsiness Detection System** is a machine vision-based project designed to enhance driver safety by detecting signs of fatigue in real-time. This system uses facial landmark detection and eye-tracking algorithms to monitor the driver's eye aspect ratio (EAR) and alert them if drowsiness is detected.

Key Features:
- Real-time detection of drowsiness using a webcam feed.
- Alerts via alarms when the driver shows signs of fatigue or yawning.
- Cross-platform compatibility with both Windows and Ubuntu operating systems.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Technologies Used](#technologies-used)
4. [System Requirements](#system-requirements)
5. [Testing](#testing)
6. [Future Scope](#future-scope)
7. [Contributing](#contributing)
8. [License](#license)

## Installation
To set up the Drowsiness Detection System on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/arukutiyash/Accepted-Journal.git
   cd Accepted-Journal
2.Install dependencies: pip install numpy scipy playsound dlib imutils opencv-python
3. Usage:python drowsiness_yawn.py --webcam 0

Technologies Used
Python : Core programming language.
OpenCV : Captures and processes video streams.
Dlib : Detects facial landmarks.
Imutils : Provides convenient functions for OpenCV.
Scipy : Calculates Euclidean distances between eyelids.
System Requirements
Python 3.x
Libraries: Numpy, Scipy, Playsound, Dlib, Imutils, OpenCV
A laptop or desktop computer with basic hardware.
A webcam for capturing video input.
Testing
The system was tested under various conditions, including different lighting, face angles, and the presence of glasses. Test results demonstrate reliable performance.

Future Scope
Incorporate parameters like blink rate and heart rate monitoring.
Integrate the system with vehicle control systems.
Extend the application to other domains, such as streaming services.![Screenshot 2025-03-04 134437](https://github.com/user-attachments/assets/09946db8-5f48-4a41-b7dd-acf68ef43419)

