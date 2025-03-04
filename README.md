# Accepted-Journal
Drowsiness Detection System
Overview
The Drowsiness Detection System is a machine vision-based project designed to enhance driver safety by detecting signs of fatigue in real-time. This system uses facial landmark detection and eye-tracking algorithms to monitor the driver's eye aspect ratio (EAR) and alert them if drowsiness is detected. By addressing the critical issue of driver fatigue, this project aims to reduce road accidents caused by inattentiveness 4.

Key features of the system include:

Real-time detection of drowsiness using a webcam feed.
Alerts via alarms when the driver shows signs of fatigue or yawning.
Cross-platform compatibility with both Windows and Ubuntu operating systems.
Scalable design with potential for future enhancements like heart rate monitoring and integration with vehicle systems 26.
Table of Contents
Installation
Usage
Technologies Used
System Requirements
Testing
Future Scope
Contributing
License
Installation
To set up the Drowsiness Detection System on your local machine, follow these steps:

Clone the Repository
bash
Copy
1
2
git clone https://github.com/yourusername/drowsiness-detection-system.git
cd drowsiness-detection-system
Install Dependencies
Ensure you have Python 3 installed. Then, install the required libraries using pip:
bash
Copy
1
pip install numpy scipy playsound dlib imutils opencv-python
Download Pre-trained Models
Download the pre-trained shape predictor model (shape_predictor_68_face_landmarks.dat) from dlib.net and place it in the project directory 7.
Usage
Run the system using the following command:

bash
Copy
1
python drowsiness_yawn.py --webcam 0
Replace 0 with the index of your webcam if you have multiple cameras connected.
The system will display a live video feed, analyze the driver's face, and trigger alerts if drowsiness or yawning is detected.
Example Output:

A green contour will be drawn around the eyes and mouth.
If drowsiness is detected, the system will display "DROWSINESS ALERT!" and sound an alarm.
If yawning is detected, the system will display "Yawn Alert" and suggest taking fresh air.
Technologies Used
This project leverages the following technologies and libraries:

Python : The core programming language used for implementation 11.
OpenCV : For capturing and processing video streams from the webcam.
Dlib : For facial landmark detection using 68 predefined points 13.
Imutils : Provides convenient functions for OpenCV.
Scipy : Used for calculating Euclidean distances between eyelids.
Numpy : For numerical computations and array manipulations.
