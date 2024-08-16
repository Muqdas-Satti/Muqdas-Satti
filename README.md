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
  - Video timing controller
  - Clocking Wizard

## Getting Started

### Requirements
- **Vivado 2019.1 or later**
- **ZedBoard**

### Steps to Build and Run
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/ZedBoard-VGA-TPG-Baseline.git
   cd ZedBoard-VGA-TPG-Baseline

#ZedBoard-VGA-TPG-Baseline/
├── src/                     # Source files
├── sim/                     # Simulation files (optional)
├── docs/                    # Documentation
├── ZedBoard_VGA_TPG_Baseline.xpr  # Vivado project file
└── README.md                # Project overview


