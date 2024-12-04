---
layout: default
title: Simulation Integration
parent: Cenceptual Aspects
nav_order: 6
---


# Integration between QEMU and Gazebo

The integration between QEMU and Gazebo is the core of our project, enabling communication between the software running on the QEMU emulator and the Gazebo simulation. This integration allows the embedded software, compiled as a binary for the Blue Pill development board, to interact with the simulated environment, providing a seamless testing and validation process without relying on physical hardware.

This connection is achieved through a ROS WebSocket. By enabling QEMU to subscribe to a ROS topic, we established a communication link between the emulated hardware and the simulated world. The ROS WebSocket facilitates the exchange of data between the QEMU-emulated Blue Pill and the Gazebo simulation, enabling the system to process sensor data, execute control commands, and simulate the robot's movement in real time.

![integration](/assets/imgs/desenhos%20tcc-context.png)

With this setup, we are able to simulate a Pioneer 2 robot in a Gazebo environment, following the exact same commands from the binary that would run on a real Blue Pill development board. This integration makes it possible to test and validate the embedded software in a realistic simulated environment, streamlining the development process and reducing dependencies on physical components.

