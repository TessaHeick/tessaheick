---
title: "LED Audio Frequency Display"
excerpt: "Custom PCB that displays of high and low frequency content of audio inputs."
layout: single
---

## Idea
Visually capture high and low frequency content of different audios using a custom PCB. 

## Solution
Designed and implemented a PCB which conditions, filters, splits, and displays audio inputs
using KiCad. Identified ideal cutoff frequencies for a baseline song (Last Christmas by Wham!) from
which to design second order filters. 

## System Design
- One analog driver, one PWM driver for a more interesting design!
- Differently colored LEDs, with circuitry designed to each's unique characteristics. 
- Dual-option power system: by waveform generator or battery.

<video width="800" controls>
  <source src="{ '/assets/images/VisualizerVideo.mp4' }" >
</video>


## Skills & Tools
- KiCad
- PCB Design and Testing
- Oscilloscope
- Filtering & Frequency Analysis
- Datasheet Literacy
