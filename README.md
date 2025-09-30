# Robotics Course Mini-Projects

This repository contains implementations from four mini-projects completed as part of a Mechatronics & Robotics course at the University of Tehran. These projects explore practical aspects of robotic systems, including sensor integration, kinematic analysis, simulation, and control environments. Each project involved hands-on coding, problem-solving, and validation through simulations or hardware setups.

## Mini-Project 1: Motion Sensing and Control with MPU-6050
- Integrated the MPU-6050 sensor (accelerometer and gyroscope) with Arduino for capturing orientation data (roll, pitch, yaw).
- Implemented calibration and filtering techniques to process raw sensor readings, plotted angles using serial tools for comparison.
- Applied sensor data to create a simple game controller and performed motion tracking using computer vision libraries like MediaPipe.
- Key tools: Arduino IDE, C++ libraries for sensor communication and data filtering.
<img width="546" height="664" alt="image" src="https://github.com/user-attachments/assets/0a1020d4-843d-4d1a-aca5-20a5cb2dec12" />

## Mini-Project 2: Kinematics and Dynamics of SCARA Robot
- Analyzed the ABB IRB 910SC SCARA robot model, solving forward and inverse kinematics using Denavit-Hartenberg parameters.
- Derived Jacobian matrix and dynamic equations, simulated motion in MATLAB/Simscape for trajectory tracking (e.g., "4567" path).
- Compared analytical models with simulation results to minimize errors.
- Key tools: MATLAB for scripting kinematics, dynamics, and visualization.

## Mini-Project 3: Robot Operating System (ROS) in TurtleSim
- Developed Python scripts in ROS to manipulate virtual turtles in the TurtleSim environment: killing the default turtle, spawning multiple turtles to form characters, and rotating them.
- Added keyboard control for turtle movement using ROS topics and services.
- Handled errors and visualized node graphs with rqt tools.
- Key tools: ROS Noetic, Python for service clients, publishers, and subscribers.

## Mini-Project 4: Object Recognition for Automated Packaging
- Explored versions of object detection frameworks (YOLOv1 to YOLOv8) and their improvements in speed and accuracy for identifying items in images.
- Calculated performance metrics like mean Average Precision (mAP) to evaluate detection quality.
- Created a custom dataset for robotic pick-and-place tasks in food packaging, focusing on locating and segmenting objects for efficient handling.
- Key tools: Python, computer vision libraries for processing images and generating grasp points.

These projects demonstrate skills in mechanical engineering principles, programming (MATLAB, Python, C++), simulation environments (Simscape, ROS), and sensor/hardware integration. They highlight challenges like error minimization, real-time control, and system optimization. Code, reports, and videos are included for each project. Feel free to ask me if you have any questions!
