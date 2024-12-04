---
layout: default
title: ROS
parent: Cenceptual Aspects
nav_order: 4
---

# What is ROS ?

ROS (Robot Operating System) is an open-source framework designed to simplify the development of robot software. It provides a set of libraries and tools that help developers build robot applications by offering functionalities such as hardware abstraction, device drivers, communication between components, and various algorithms for planning, control, and simulation. ROS is widely used in the robotics community due to its modular architecture, flexibility, and scalability.

## How ROS Works

ROS works by providing a communication system called ROS Topics and ROS Services, which allow different parts of a robot system (like sensors, controllers, and algorithms) to exchange data. Components in ROS are structured as nodes, each responsible for a specific task. These nodes communicate with each other over a publish-subscribe model (for Topics) or a client-server model (for Services). ROS also offers powerful tools like RViz for visualization, rosbag for logging, and roslaunch to launch multiple nodes with predefined configurations. This modularity allows developers to design complex robotic systems with easily interchangeable parts.

In addition, ROS can be integrated with simulation tools like Gazebo to simulate robot behavior in a controlled environment before actual deployment. This interaction enables developers to test algorithms, sensors, and other components in realistic environments without needing physical hardware.

## Why we are using ROS

We are using ROS in this project because it provides a seamless way to connect and coordinate the various components of our system. ROS handles the communication between the Blue Pill emulation (running on QEMU) and the Gazebo simulation environment, using ROS topics to send and receive messages. This integration allows us to simulate the robot's physical behavior and sensor data, ensuring that the software can be validated in a realistic environment before deployment on actual hardware. 
