# NOMOUSE

This project builds a object detection (stop sign, traffic light and car) in prototype self-driving system (RC car) using Raspberry Pi, Arduino and open source software. 

Raspberry Pi collects inputs from a camera module and an ultrasonic sensor, and sends data to a computer wirelessly. The computer processes input images and sensor data for object detection (stop sign and traffic light) and collision avoidance respectively. A neural network model runs on computer and makes predictions for steering based on input images. Predictions are then sent to the Arduino for RC car control. 
