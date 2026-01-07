---
title: "Remote Garden Monitoring System"
excerpt: "Low-power embedded system for long-range environmental monitoring."
layout: single
header:
  image: assets/images/IMG_9813.PNG
  teaser: assets/images/IMG_9813.PNG
---

## Problem
Traditional gardening requires frequent check-ins and plants are at risk from animal destruction. Available garden-monitoring tools are generally expensive or scaled for industrial-level production. 

## Solution
Designed and implemented a low-power embedded system for remote monitoring of soil metrics and animal activity in outdoor environments. The system was optimized for long-duration, solar-powered deployment and reliable long-range wireless communication. Seamlessly integrated user interface for display of metrics, with both historical and up-to-date information. 

## System Design
- STM32-based microcontrollers running C-based firmware
- Sensors for soil moisture, temperature, and motion (PIR)
- Solar power management subsystem
- LoRa P2P communication

## Key Technical Decisions
- Selected LoRa to balance range, power consumption, and data rate
- Implemented timed sensing intervals and aggressive sleep modes
- Calibrated sensors in circuitry and firmware to improve measurement accuracy

## Results
- Achieved reliable (<25% packet loss) long-range data transmission up to 1 mile
- System duration of 8 days on one charge (~12.5mAh average consumption)
- Stable sensor readings across environmental conditions, including rain

## Skills & Tools
- Embedded C
- STM32 microcontrollers
- Low-power system design
- LoRa / RF communication
- Sensor integration and calibration
- Power optimization techniques

