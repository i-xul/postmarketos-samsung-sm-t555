# postmarketOS on Samsung Galaxy Tab A 9.7 LTE (SM-T555)

This repository documents my postmarketOS installation and bring-up notes for the Samsung Galaxy Tab A 9.7 LTE (SM-T555).

The original install process was not fully documented step by step at the time, but this repository captures the important technical outcome: what was used, what works, what needed attention, and the device's current status after installation.

## Overview

The goal of this project was to get a Linux-based operating system running on an older Android tablet and evaluate its usefulness as a lightweight Linux device.

The device now runs postmarketOS with XFCE4 and is booting successfully.

## Device

- **Model:** Samsung Galaxy Tab A 9.7 LTE
- **Variant:** SM-T555
- **Original OS:** Android
- **Target OS:** postmarketOS
- **Boot method used:** lk2nd + fastboot
- **Installed desktop environment:** XFCE4

## Why this project matters

This was not a standard desktop Linux installation. It required working with a non-traditional target device, alternative boot methods, and device-specific quirks.

From a technical perspective, this project involved:

- low-level boot and installation steps
- device-specific troubleshooting
- Linux deployment on unsupported / uncommon hardware
- practical validation of the final working system

## What was used

- postmarketOS
- lk2nd
- fastboot
- XFCE4

## Current status

### Working
- system boots successfully
- postmarketOS is installed
- XFCE4 desktop environment runs
- device is usable as a Linux tablet test platform

### To be verified / documented further
- touch input
- audio
- Wi-Fi
- Bluetooth
- LTE / mobile connectivity
- cameras
- power management / battery behavior
- suspend / resume behavior

## Notes about documentation

The full installation process was not originally preserved as a complete step-by-step log.  
This repository is therefore focused on:

- documenting the successful end result
- summarizing the boot/install approach that was used
- recording the current working state of the device
- preserving the project as a technical reference for future work

## Technical summary

The tablet was brought up using the lk2nd + fastboot route and postmarketOS was installed successfully.  
The system now runs XFCE4 and serves as a practical example of repurposing older ARM-based consumer hardware into a Linux environment.

## Lessons learned

- older Android hardware can be repurposed into useful Linux test platforms
- success depends heavily on device-specific boot methods and compatibility
- documenting the process early would have made later reconstruction easier
- even when the full install path is not preserved, the project still has value if the final state and technical observations are documented clearly
- ARM/Linux projects on older consumer devices require patience, iterative testing, and willingness to work through incomplete documentation

## Future improvements

- reconstruct the installation process more precisely
- document package management and system updates in postmarketOS
- test hardware support in detail
- benchmark usability for lightweight daily tasks
- compare postmarketOS with other possible Linux-based options for older tablets

## Repository purpose

This repository is mainly a technical documentation project rather than a software development project.

It exists to show:

- Linux experimentation on uncommon hardware
- practical troubleshooting ability
- device bring-up work
- technical documentation of a successful port/install outcome

## License

MIT
