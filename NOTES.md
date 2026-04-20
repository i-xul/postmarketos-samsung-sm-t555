# Project Notes

## Background

This project started as an experiment to repurpose an older Android tablet into a usable Linux device.

The original installation process was not fully documented step-by-step at the time.  
This repository instead focuses on capturing the resulting system, technical approach, and observations.

## Installation approach (high-level)

- lk2nd used as secondary bootloader
- fastboot used for flashing / booting
- postmarketOS installed successfully
- XFCE4 selected as lightweight desktop environment

## Observations

- Installing Linux on consumer Android hardware is highly device-specific
- Documentation across sources can be fragmented or incomplete
- Small configuration differences can determine success or failure
- Iterative testing and persistence are required

## Challenges encountered

(Exact steps not preserved, but based on experience:)

- Boot process inconsistencies
- Device-specific quirks during bring-up
- Trial-and-error required during installation
- Limited or scattered documentation

## Key takeaway

Even without full process documentation, achieving a working Linux system on unsupported hardware demonstrates:

- understanding of alternative boot chains
- ability to troubleshoot non-standard environments
- persistence in solving low-level issues

## Future direction

- Reconstruct the install process more precisely (if repeated)
- Test and document hardware support in detail
- Explore performance tuning and power management
- Evaluate real-world usability of the device

## Personal note

This project reinforced the importance of documenting complex setups early.  
Future similar projects will include step-by-step logging from the beginning.
