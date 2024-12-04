---
layout: default
title: QEMU
parent: Cenceptual Aspects
nav_order: 3
---

# What is QEMU ?

QEMU (Quick Emulator) is an open-source hardware emulator that allows you to run operating systems and programs for one architecture on a different architecture. It enables the virtualization of entire computer systems, including the processor, memory, and peripheral devices, providing a powerful and flexible environment for testing and development.

## How QEMU Works

QEMU functions by emulating the hardware of a target system, allowing software written for that system to run on a host machine. It uses dynamic translation to execute instructions in a way that mimics the behavior of the target hardware. For improved performance, QEMU can work in conjunction with Kernel-based Virtual Machine (KVM), a Linux kernel module that enables hardware virtualization. KVM allows QEMU to directly access the host machine’s hardware, resulting in faster emulation and more efficient use of resources. This combination of QEMU and KVM makes it an ideal solution for simulating embedded systems and testing software before deployment on physical hardware.

## Why are we using QEMU ?

In our project, QEMU is used to simulate the Blue Pill development board, a widely used ARM-based microcontroller board. By emulating the Blue Pill with QEMU, we can run and test the embedded software without needing the physical board. This emulation is integrated with the Gazebo-simulated environment, where we simulate real-world physics and interactions, such as sensor readings and movement. 