# WindBorne Firmware Application Portfolio

**Syamdilya Nimmagadda**

This repository contains selected hardware, RTL, verification, and embedded-related work relevant to firmware and hardware/software boundary engineering.

## Resume

* [View My Resume](./Nimmagadda_Resume.pdf)

## WindBorne Informal Questions

* [Questions PDF](./WindBorne_Informal_Questions.pdf)

## Featured Project: SPI Slave with Flow Control

Implemented an SPI Slave with protocol-level flow control using dual-clock RX/TX FIFOs, watermark-based backpressure, BUSY-token handling, and status-first polling. Built a UVM-style testbench with randomized SPI modes and frame lengths, self-checking scoreboard, and SystemVerilog Assertions for CS/SCK timing and FIFO safety. Used Python scripts to analyze throughput and FIFO usage.

## Other Relevant Projects

### DMA Controller Verification

Verified DMA controller functionality including single transfer, burst, and scatter-gather modes. Developed UVM testbench components such as agents, monitors, and scoreboards, and created functional coverage for transfer size, burst type, and channel priority.

### RTL Design and Verification of 4-Port Switch/Router

Co-implemented a parameterized 4-port switching datapath with per-port FIFOs and store-and-forward behavior. Built a UVM-style verification environment with constrained-random traffic, coverage reporting, SVA assertions, and Python-based log analysis.

### Router 1x3 Design and Verification

Designed and synthesized a 1x3 router in Verilog with Register, FIFO, FSM, and Synchronizer submodules. Built a UVM-based verification environment and used regression testing and assertions for RTL sign-off.

### Third Eye for the Blind Using Arduino

Built an IoT and embedded systems project using Arduino to assist visually impaired users through sensor-based obstacle detection and feedback.
