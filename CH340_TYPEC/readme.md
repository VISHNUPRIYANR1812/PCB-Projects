# CH340 USB to Serial Converter (Type-C)

This project is an open-source USB to TTL (UART) converter based on the **CH340** chip, designed with a **USB Type-C** connector. It is created using **KiCad** and can be used for serial communication with microcontrollers, debugging, and interfacing with UART-based devices.

## Features

- **CH340G** USB-to-Serial Converter IC  
- **USB Type-C** Connector for modern compatibility  
- Supports **3.3V & 5V logic levels**  
- LED Indicators for **TX & RX activity**  
- **Compact PCB design** for easy integration  

## Hardware Design

The PCB is designed in **KiCad** and includes the following key components:

![image](https://github.com/user-attachments/assets/df1052be-49e6-4bba-b76b-0343a131d0aa)


- **CH340G** IC for USB to UART conversion  
- **USB Type-C** port for improved connectivity  
- **1.5K pull-up resistors** on D+ and D- lines for USB communication  
- **16MHz Crystal Oscillator** for stable clock operation  
- **1N4148 Diodes** for circuit protection  
- **Capacitors & Resistors** for power stability and signal integrity  

### Schematic & PCB Layout

Schematic and PCB layout files are available in the repository.  

A preview of the PCB layout:  

![TOP](https://github.com/user-attachments/assets/15fbb5f0-6906-4bda-93ba-f2ba66fa558d)

![BOTT](https://github.com/user-attachments/assets/8e0d9df9-a963-4d85-bf9c-070d0687ca32)


