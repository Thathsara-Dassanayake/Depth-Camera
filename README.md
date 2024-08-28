# Depth-Camera Using Computer Vision

![image](https://github.com/user-attachments/assets/1bb8ec3f-4448-41b2-be54-42bb0ab67134)
The project focuses on designing a Depth Camera using computer vision techniques, object detection, and feature matching to create a portable and cost-effective solution for accurate depth measurement. The key aspects of the project include:

1.  Hardware Design:

* The project involved selecting and configuring components such as a stepper motor, microcontroller (ATmega328P), and a USB Type-C adapter.
* A 3D-printed cylindrical enclosure was designed to house the components, ensuring structural integrity and ease of assembly.

2. Software Integration:
* Algorithms were developed for image capturing, camera calibration, object detection using YOLOv8, feature detection using SIFT algorithm, feature matchig using BFMatcher with NORM L2 norm., and depth calculation.
* The camera calibration process involved both mono and stereo calibration, providing the necessary parameters for accurate depth measurement.

3. System Optimization:

* The project included power management strategies and optimization of overall system performance.
* Integration of the stepper motor allowed the camera to capture images from multiple angles, aiding in depth calculation.

4. Testing and Evaluation:
* Extensive testing was conducted to ensure the accuracy and robustness of the system, including calibration, object detection, feature matching, and motor control.
* The YOLOv8 model was custom-trained to improve object detection accuracy, a critical component of the system.

5. Group Collaboration:
* The project was a team effort where each member contributed their expertise to different aspects of the design, implementation, and testing.
* Team members collaborated on problem-solving, particularly in areas like camera calibration, motor integration, and algorithm optimization.

https://github.com/user-attachments/assets/b677afcc-1f56-4e24-a2f9-319fe8ce68ad

## Software Integration and Programming Analysis
This section provides a comprehensive overview of the programming aspects of our depth camera
project, detailing the implementation and testing processes involved in capturing images, calibrating cameras, detecting objects, matching features, and calculating depth.

1. Capturing the Image
* Implement a code to capture a photo from the USB webcam when the ’S’ key is pressed.
* Used OpenCV to interact with the USB webcam and capture images. The
code allows capturing images by pressing the ’S’ key and exits on pressing ’Q’ or interrupt.
