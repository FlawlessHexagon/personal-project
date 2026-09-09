# [64] Bluetooth AWD Arduino Motorized Vehicle

## Classification
- Topic: Embedded systems & robotics / wireless hardware communication
- Evidence status: Primary open-source firmware & hardware implementation; showcase-only

## Project
- Goal: Build and program an all-wheel-drive (AWD) robotic vehicle controlled wirelessly via smartphone Bluetooth signals.
- Product: An autonomous/manual 4WD robotic vehicle powered by an Arduino microcontroller and HC-05 Bluetooth transceiver with custom serial firmware.

## Why it succeeded
- Implemented robust serial communication decoding to translate incoming Bluetooth character commands into motor driver H-bridge state changes.
- Completed physical fabrication and firmware deployment (no public IB score is available).

## Useful lesson
Implementing a watchdog timer and default stop states on loss of wireless serial communication prevents runaway robotics accidents during testing.

## Sources
- GitHub Repository: https://github.com/Tooweisian/Programming-Made-Easy
- Arduino Firmware Source: https://github.com/Tooweisian/Programming-Made-Easy/blob/master/FinalProject.ino
