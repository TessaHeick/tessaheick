---
title: "Analog Signal Emulator"
excerpt: "STM-32 based analog signal playback system with integrated external memory."
layout: single
---

## Goal
Use I2C to read and write from external memory, using Serial Data (SDA) and Serial Clock (SCL) lines, leveraging HAL library functions. 

## Solution
Design two functions for reading and writing, which use a variety of indicators (chip select, device ready, etc.) to transmit to and read from memory. Then, this was integrated with ADC and DAC peripherals to sample and recreate signals. These functions are verified firstly with debugger tools and stepthroughs with breakpoints (using a testbench), then with a waveform generator and oscilloscope. 

## System Design
- STM32-based microcontrollers running C-based firmware
- SCA, SCL, VDD, and gnd connections to M24M01 chip (external EEPROM memory)
- Testing: Waveform generator and oscilloscope connected to DAC and ADC peripherals. 

## Key Technical Decisions
- Calibrating timing parameters to maintain waveform accuracy and prevent aliasing

## Skills & Tools
- Embedded C
- STM32 microcontrollers
- STM32 Cube IDE
- External memory integration and mapping

