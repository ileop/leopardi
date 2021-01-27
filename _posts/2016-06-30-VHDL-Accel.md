---
layout: post
title:  "VHDL: Nexys4DDR board built-in accelerometer data acquisition and displaying"
date:   2016-06-30 12:30:24 +0100
categories: unitn
---
* Jun 2016
* unitn bsc
* Authors:
    * Andrea Leopardi
    * [Davide Marcantonio](https://www.linkedin.com/in/davidemarcantonio/)

# Summary
This project aimed at extracting the 3-axis acceleration values from the built-in accelerometer of the **Nexys4DDR** board. In particular the accelerometer is an `ADXL362` and it is connected through the `SPI` interface with the FPGA controller. We used a library to manage the SPI protocol and then built an architecture to read and visualize the data on the 7-segments, along with an attitude saving and comparison. The board was programmed in `VHDL` with the **Vivado** tool.