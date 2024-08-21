# ZedBoard VGA Test Pattern Generator

This repository contains a baseline FPGA design for the ZedBoard, demonstrating the use of the Test Pattern Generator (TPG) to output video patterns via VGA. The project is implemented using Xilinx Vivado and is intended to serve as an introduction to video signal generation on the ZedBoard.

## Overview
The project features:

- **Test Pattern Generator (TPG):** Generates video patterns like color bars and checkerboards.
- **VGA Output:** Displays patterns on a VGA monitor connected to the ZedBoard.

## Hardware and IP Cores
- **Board:** ZedBoard (Zynq-7000 SoC)
- **Resolution:** VGA 640x480
- **Key IP Cores:**
  - Test Pattern Generator (TPG)
  - AXI4-Stream to Video Out
  - Video Timing Controller
  - Clocking Wizard

## Getting Started

### Requirements
- Vivado 2019.1 or later
- ZedBoard

### Steps to Build and Run
1. Clone the Repository:
    ```bash
    git clone https://github.com/Muqdas-Satti/Zynq7000-vivado-VGA.git
    cd Zynq7000-vivado-VGA
    ```

2. Explore the Project Structure:
    ```
    ZedBoard-VGA-TPG-Baseline/
    ├── src/                          # Source files
    ├── sdk/                          # SDK files
    ├── ZedBoard_VGA_TPG_Baseline.xpr # Vivado project file
    └── README.md                     # Project overview
    ```

3. For those who do not have Vivado 2019.1 and want to build the project from scratch, follow the detailed tutorial on my blog:  
   [**Build ZedBoard-VGA-Test Pattern Generator from Scratch**](https://muqdas-satti.github.io/)

This tutorial covers everything from setting up your environment to implementing the design without needing Vivado 2019.1.

Feel free to reach out if you have any questions or need further assistance!
