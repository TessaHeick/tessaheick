---
title: "Industry Experience: Flash Memory Driver"
excerpt: "C-based integration layer for database management software."
layout: single
---
## Context
This is a project I completed as an embedded software engineering intern for McObject LLC. You can read more about the 
increasing relevance of these projects in an article I co-authored [here](https://www.embedded.com/real-time-database-management-on-raw-flash-memory-from-complex-infrastructure-to-streamlined-drivers).

I've also spoken on my experience working on this project on my [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7374857706152808448/).

## Problem
Proprietary database management software for raw flash memory needed to be run specifically on an STM32 microcontroller. 
Thus, an adaptation layers were required to integrate the software's accessing functionality with the microcontroller's 
connection to external memory.

## Solution
Using STM's HAL library, intermediate layers between the management software and raw flash were developed.
This layer needed to operate efficiently enough to maintain dependancy and determinism. Firstly, single-SPI was 
deployed, then upgraded to Quad-SPI for minimal latency. 

## System Design
- STM32-based microcontroller running C-based firmware
- Quad-SPI connection to external flash memory
- Leverage of existing HAL library
- Compliance with flash memory design and access style

## Results
- Software passed standardized testbench with minimal latency
- Software was integrated with company codebase, offering clients the option to use STM32 microcontrollers with the database management software.

## Skills & Tools
- Embedded C
- STM32 microcontrollers
- Datasheet understanding and application
- Memory management/external memory integration
- Logic analyzer
