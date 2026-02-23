# 8085 Microcomputer System Design

## Overview

This project presents the design of a complete microcomputer system built around the Intel 8085 microprocessor. The system integrates memory modules, programmable I/O devices, timer subsystems, and keyboard/display control through hardware address decoding.

The goal is to understand system-level computer architecture by combining CPU, memory, and peripheral components into a functional microcomputer.

---

## System Architecture

The system includes the following major components:

- Intel 8085 Microprocessor
- EPROM (2764)
- RAM (6264)
- 74LS373 Address Latch
- 74LS138 Address Decoder
- 8255 Programmable Peripheral Interface
- 8253 Programmable Interval Timer
- 8279 Keyboard/Display Controller
- Clock and Reset circuitry

All devices communicate via the address, data, and control buses of the 8085.

---

## Key Features

- Full 16-bit address space (64 KB)
- Hardware address decoding
- Memory-mapped I/O
- Programmable parallel I/O ports
- Timer-based operations
- Keyboard and display interfacing

---

## Memory Organization

The 8085 provides a 16-bit address bus capable of addressing 64 KB of memory.  
Memory and peripherals are mapped using decoding logic implemented through the 74LS138.

(Detailed memory map to be added.)

---

## Future Enhancements

- Digital schematic recreation (Proteus/KiCad)
- Assembly program demonstrations
- Interrupt handling implementation
- System simulation and validation

---

## Author

Kedar Modak  
B.Tech Electrical Engineering  
Shri G. S. Institute of Technology and Science, Indore
