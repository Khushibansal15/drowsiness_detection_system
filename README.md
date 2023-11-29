# drowsiness_detection_system
Overview
This project implements a driver drowsiness detection system using a Convolutional Neural Network (CNN) with the Keras library. The goal is to identify signs of driver drowsiness based on facial images captured through a camera. The system now includes a real-time video capture feature for enhanced usability.

Project Components
Data Preparation: The dataset is organized into training and testing sets, containing images of drivers with different levels of alertness.

Model Architecture: The CNN architecture is designed using Keras, consisting of convolutional layers, max-pooling layers, and fully connected layers for effective feature learning.

Real-time Video Capture: The project now includes a real-time video capture feature, enabling the system to analyze live video streams from a connected camera.

Training: The model is trained on the labeled dataset to learn patterns and features indicative of drowsiness in facial expressions.

Evaluation: The trained model is evaluated on a separate test set to assess its performance in accurately detecting drowsiness.

Model Saving: The final trained model is saved in the HDF5 format for future use.
DATASET:

Dataset could be imported from following link: https://www.kaggle.com/datasets/serenaraju/yawn-eye-dataset-new

Dependencies
Python 3.x
Keras
TensorFlow (or other compatible backend)
OpenCV
NumPy
pygame
Other dependencies as listed in the project files.
Usage
Install dependencies using requirements.txt.
Organize the dataset into the specified directory structure.
Execute the provided Python script for real-time video capture, training, and evaluation.
Adjust hyperparameters and model architecture as needed.
Acknowledgments
This project is inspired by the need for intelligent systems to enhance driver safety and prevent accidents caused by drowsiness. The addition of real-time video capture enhances the practicality of the system for real-world applications. The project serves as a foundation for further exploration and improvement in the field of computer vision and driver assistance systems.

