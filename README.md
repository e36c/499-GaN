# GaN Motor Driver
![PCB render](non-code/media/board_render.jpg?raw=true "PCB render")

This repo contains the design files, code, and final report for my work on a GaN FET motor driver for an EE499 independent project with Professor Alan Sahakian at Northwestern University. All code is my own. No non-standard libraries were used, including to achieve position and speed control.

The custom PCB is capable of:
- 48 V DC supply
- 53 A phase current
- Full-range current and voltage measurements
- Running at high frequency
- Overcurrent protection

As of the end of SP26, there is code for position and speed control. This is a live repo, as I continue work on speeding up the basic control code as well as full vector control.

See [final report](non-code/final_report.pdf) for more details.