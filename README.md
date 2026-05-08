# VI-Char-Diode-PCB
A microcontroller-based automated V-I characteristics measurement system designed for analyzing diode behavior.
The project uses the STM32 microcontroller for data acquisition and control, enabling real-time measurement and visualization of diode voltage-current characteristics through a Python-based plotting interface.

## Overview
The system measures the voltage and current characteristics of a diode placed in the test slot on the PCB.
The STM32 microcontroller controls the measurement process, acquires analog data, and transmits the readings to a computer through a USB-to-UART interface.
A Python application running on the PC receives the serial data and plots the V-I characteristics in real time.

<img width="376" height="401" alt="Screenshot 2026-05-09 at 5 01 43 AM" src="https://github.com/user-attachments/assets/477f8e79-9bbb-403d-8565-2e20b4a42be6" />

