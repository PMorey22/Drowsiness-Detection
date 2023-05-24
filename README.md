# Drowsiness Detection using Facial Landmarks and Eye Blinking

This project utilizes facial landmarks and eye blinking to detect drowsiness in real-time using OpenCV, Dlib, and NumPy libraries. The project focuses on analyzing the eye blink patterns of an individual and determining their level of drowsiness based on predefined thresholds.

## Table of Contents

- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Execution Steps](#execution-steps)
- [Additional Information](#additional-information)

## Introduction

Drowsiness Detection is an essential aspect of ensuring driver safety, especially in long-duration journeys. This project aims to detect drowsiness by analyzing facial landmarks and monitoring eye blink patterns. By utilizing computer vision techniques, the project provides real-time feedback on the driver's drowsiness level, allowing them to take appropriate actions to prevent accidents.

## Dependencies

To run this project, the following dependencies are required:

- OpenCV (`cv2`) - For basic image processing functions.
- NumPy (`numpy`) - For array-related functions.
- Dlib (`dlib`) - For deep learning-based modules and face landmark detection.
- Imutils (`face_utils`) - For basic operations of conversion.

Make sure to install these dependencies before running the project.

## Execution Steps

To execute the Drowsiness Detection project, follow these steps:

1. Clone the project repository:

```shell
git clone https://github.com/PMorey22/Drowsiness-Detection.git

2. Install the project dependencies:
pip install -r requirements.txt

3. Download the pre-trained shape predictor model:
You need to download the pre-trained shape predictor model file "shape_predictor_68_face_landmarks.dat". You can download it from the following link:

shape_predictor_68_face_landmarks.dat

Once downloaded, extract the file and place it in the project directory.

4. Execute the project:
python drowsiness_detection.py

5. Drowsiness Detection in action:
The program will start the camera feed and analyze the eye blink patterns in real-time. The output window will display the video feed along with the detected faces, facial landmarks, and the drowsiness status.

6. Terminate the program:
To stop the execution, press the 'Esc' key.
