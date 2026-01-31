# Keyword Spotting-Driven Attention Bias for Vision: playground

This repository aims to explore initial strategies for using the output of an FPGA-implemented Graph Convolutional Neural Network (GCNN) for keyword spotting (KWS) to generate a spatial bias in an event-driven camera's attention model. The core challenge is bridging the gap between a discrete keyword detection and a continuous, spatial attention bias.

## System Overview

### Components: 
- Waveform to event audio converter 
- GCNN Keyword Spotting (running on FPGA)
- Frame-based to event-based video converter
- File format converter 
- Bio-inspired attention model for visual processing