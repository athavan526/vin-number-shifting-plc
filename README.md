# VIN Number Shifting Logic with Index Registers & HMI Display (GX Works3 + GOT)

This repository contains a complete solution for VIN number shifting logic using index registers, developed in **GX Works3** for Mitsubishi PLCs. It also includes an **HMI (GOT)** screen design to visually display the VIN shift results in real time.

## Overview

- **Platform:** Mitsubishi PLC (GX Works3) & Mitsubishi GOT HMI
- **Core Logic:** Index register-based VIN shifting
- **HMI Feature:** Real-time display of shifted VIN on GOT touchscreen
- **Files Included:**
    - PLC program
    - HMI screen project
    - Simulation video demonstrating both PLC logic and HMI interaction


## Usage

https://github.com/user-attachments/assets/c5a27258-7a72-4db9-a8ae-94c180c8af76



1. **PLC Logic:**
    - Open GX Works3 and import `vin_shifting.gx3`
    - Load onto compatible Mitsubishi PLC hardware or use GX Works3 simulator

2. **HMI Screen:**
    - Open GOT Designer (or GT Works3) and load `got_hmi_project.got`
    - Connect HMI to the PLC to display shifted VIN on screen

3. **Run Simulation:**
    - Use provided `sample_vins.txt` for test VINs
    - Watch `simulation_video.mp4` for demonstration of both PLC logic and HMI screen

## HMI Features

- Displays current VIN string and shifted output
- User-friendly touchscreen interface on Mitsubishi GOT HMI
- Real-time updates as data is shifted in PLC

## Requirements

- **Software:** GX Works3 (PLC), GT Works3 or GOT Designer (HMI)
- **Hardware:** Mitsubishi PLC and GOT HMI (tested on [your model, if applicable])
- **PC:** For simulation and video playback


---

> For questions, suggestions, or contributions, please open an issue or submit a pull request.

