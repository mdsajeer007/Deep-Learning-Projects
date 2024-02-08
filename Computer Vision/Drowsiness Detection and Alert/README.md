
# Drowsiness Detection and Alert
# Objective:
The objective of this project is to develop a system that can automatically detect driver drowsiness in real-time and then emit an alert to wake the driver up. The goal is to prevent accidents that occur due to the driver falling asleep behind the wheel.


# What happens
Set the timer for 2 seconds and 5 frames per second. If the eyes were closed for 2 seconds continuously that means if the model captures continuous 10 closed eye frames then it will alert the driver by beeping the alarm sound.


Project Steps:
1. Data Acquisition:Gather the required dataset 
2. Feature Extraction: Using the training data, train machine learning models to identify signs of drowsiness like eye closure (Feature extraction)
3. Classification: If the driver matches the feature of drowsiness the alarm beeps and the alarm turns the driver back to normal


# Tech Stack
* Python - Primary programming language for implementing the project.
* Tensorflow - Focus on the training and inference of deep neural networks.
* OpenCV - for image processing and performing computer vision tasks.
* Keras - interface for artificial neural networks.
