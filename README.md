# OpenCV & MediaPipe Project Hub

This repository contains Python scripts demonstrating computer vision techniques, including a real-time "air drawing" application and an accuracy metric calculator.


# 1. MediaPipe Virtual Drawing

This is a Python application that opens your webcam and uses MediaPipe to track your hand. It identifies your index finger, allowing you to "draw" on the screen in real-time, just by moving your finger in the air.

## Key Features

### Real-Time Hand Tracking: Uses the MediaPipe Hands solution to get high-fidelity hand and finger landmarks.

Virtual "Air" Drawing: Tracks the tip of the index finger to draw a persistent line on the webcam feed.

OpenCV Powered: Built entirely with OpenCV to handle the webcam feed, process images, and display the final output.

### 2. Intersection over Union (IoU) Utility

This repository also includes a utility script for calculating the Intersection over Union (IoU) metric.

What is IoU? IoU is a standard metric used to measure the accuracy of an object detector or image segmentation model. It calculates the overlap between the "ground truth" (correct) bounding box and the "predicted" bounding box from a model.

Usage: This script provides a clear function to compute the IoU score, useful for evaluating any custom object detection or segmentation task.

# Technologies Used

Python

OpenCV (for image/video capture, processing, and drawing)

MediaPipe (for real-time hand tracking)
