
# homemade-8-bit-cpu

Watch Demo Video above!!

A homebrew 8-bit CPU designed from scratch that was inspired by classic CPUs like the 6502 and Z80.

## Why I Built This

I’m an 8th-grade student interested in CPU design, computer architecture, and how modern processors work internally.
This project is part of my journey toward building more advanced CPUs with pipelining, virtual memory, and out-of-order execution.

## Features
- 8-bit data bus
- 16-bit address bus
- Custom ISA
- Flags: Z, C, N
- Memory-mapped I/O
- Designed and implemented from scratch

## Architecture
![Schematic](images/cpu8.png)

Main components:
- ALU
- Register file
- Control unit
- Program counter
- Instruction decoder
- RAM / ROM

## Instruction Set
See [`docs/instr.txt`](docs/instr.txt)
