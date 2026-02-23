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

The 8085 has a 16-bit address bus allowing access to 64 KB of address space (0000H – FFFFH).

The system memory map is organized as follows:

| Address Range | Device | Size |
|--------------|--------|------|
| 0000H – 1FFFH | EPROM (2764) | 8 KB |
| 2000H – 3FFFH | RAM (6264) | 8 KB |
| 4000H – 40FFH | 8255 PPI | 256 B |
| 4100H – 41FFH | 8253 PIT | 256 B |
| 4200H – 42FFH | 8279 KBD/Display | 256 B |
| Remaining Space | Reserved for expansion | — |

Address decoding is implemented using the 74LS138 3-to-8 line decoder.

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
