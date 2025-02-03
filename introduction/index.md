---
title: 🏠 Home
layout: default
nav_order: 1
permalink: /
---

![QemuGazeboSim](https://raw.githubusercontent.com/qemu-gazebo-sim/qemu-gazebo-sim.github.io/main/assets/main_symbol.png)

# 🤔 What is QEMUGazeboSim? 

In the development of robot systems, testing embedded software traditionally relies on physical hardware, making it hard to proceed without the actual components. This dependency often leads to increased costs and delays. Moreover, in robotics development, identifying the root cause of an issue can be challenging due to the interplay between mechanical, electrical, and software components.

Our project goal is to combine hardware emulation and environmental simulation. By enabling testing without physical components, this solution not only reduces costs and development time but also provides a controlled environment to isolate and address potential issues with precision, ensuring reliable and efficient validation of embedded systems.

Answering the question, QemuGazeboSim is a simulation platform designed to validate embedded systems without the need for physical hardware.

## 🎯 Objective

The main goal of this work is to develop a simulator for software testing of embedded systems using STMicroelectronics microcontrollers applied to mobile robotics, enabling comparisons with real projects. The primary tools used will be Gazebo for simulating the environment and data acquisition, QEMU for hardware emulation and ROS to integrate both tools.

Using the whole project, it is expected to enable code validation before bench testing with physical devices.