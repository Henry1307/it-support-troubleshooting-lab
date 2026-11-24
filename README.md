# IT Support & PC Troubleshooting Lab

## Project Overview

A hands-on technical learning project focused on developing practical IT support, computer hardware, operating system, and troubleshooting skills.

This repository documents lab exercises, technical investigations, configurations, and solutions.

## Objectives

- Understand PC hardware components and their functions.
- Practice hardware installation and upgrades.
- Install and configure operating systems.
- Investigate common hardware and software issues.
- Perform system diagnostics and troubleshooting.
- Document technical problems and their solutions.

## Project Areas

| Area | Planned Activities |
|---|---|
| Computer Hardware | Component identification, upgrades and diagnostics |
| Windows | Installation, configuration and troubleshooting |
| Linux | Installation, commands and system administration |
| System Diagnostics | Hardware and software investigation |
| Troubleshooting | Identify problems, test solutions and verify results |

## Lab Environment

Environment and tools will be documented as the practical exercises are completed.

## Documentation

Each completed exercise will include:

- Objective
- Tools and environment
- Procedure
- Screenshots and evidence
- Problem encountered
- Troubleshooting process
- Results and lessons learned

## Project Status

In Progress

## Author

Henry Joseph Varghese


## Exercise 01: Hardware Identification

### Objective
Identify and document the hardware specifications of a computer using macOS system diagnostic tools.

### Test Environment
- Device: MacBook Air
- Model: MacBookAir10,1
- Operating System: macOS 26.6.1

### Hardware Specifications

| Component | Specification |
|---|---|
| Processor | Apple M1 |
| CPU Cores | 8 (4 Performance, 4 Efficiency) |
| GPU Cores | 7 |
| Memory | 8 GB |
| Storage | 256 GB SSD |
| Available Storage | 95.23 GB |
| File System | APFS |
| Display | 2560 × 1600 Retina |

### Tools Used
- macOS Terminal
- system_profiler
- sw_vers

### Commands Used
```bash
system_profiler SPHardwareDataType
system_profiler SPStorageDataType
system_profiler SPDisplaysDataType
sw_vers
```

### Result
Successfully identified and documented the computer's processor, memory, storage, graphics, display, and operating system.

### Skills Demonstrated
- Hardware identification
- Operating system information gathering
- Command-line fundamentals
- System diagnostics
- Technical documentation

