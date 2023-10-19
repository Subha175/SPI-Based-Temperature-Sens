# SPI-Based-Temperature-Sens


# TABLE OF CONTENT

- [Introduction](#Introduction)

# Introduction

## SPI-based TEMPERATURE MONITOR

This project will aim at design and immplemention of a SPI-based temperature monitor. The students will design a controller in Verilog to read the data from the sensor ([LM70][datasheetLM70]) using the industry-standard SPI protocol, convert the data to a human readable format (deg-C) and drive a set of 7-segment display to display the data. In order to test the Verilog code in realtime application, the Verilog code will be synthesized into a Xilinx's Spartan FPGA board. This will allow the students to test their Verilog code in real time.

![Temperature Monitor Block Diagram](docs/tempMonitor-blockDiag-v1-0322.png)
