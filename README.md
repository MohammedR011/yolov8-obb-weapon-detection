# Oriented Object Detection with YOLOv8 and Roboflow

This repository contains a complete pipeline for training and evaluating an Oriented Object Detection (OBB) model using YOLOv8 and a dataset hosted on Roboflow. The project demonstrates the power of transfer learning in computer vision, specifically for detecting objects with rotation.

# Project Overview

The goal of this project is to detect specialized objects (such as handcuffs and knives) using oriented bounding boxes. Unlike standard horizontal boxes, OBB allows the model to capture the exact orientation of objects, which is crucial for precision in various real-world scenarios.



# Key Features:

Dataset Integration: Seamlessly downloads and prepares data from Roboflow.

Transfer Learning: Utilizes the pre-trained yolov8n-obb model as a foundation.

Early Stopping: Implements a patience-based early stopping mechanism to prevent overfitting.

Visualization: Includes a custom grid-based visualization script to display predictions with confidence probabilities.

