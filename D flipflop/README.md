# D Flip-Flop Using Verilog HDL

## Introduction
A D (Data) Flip-Flop is a sequential logic circuit used to store one bit of data. It captures the value of the input D at the rising edge of the clock signal and transfers it to the output Q.

D Flip-Flops are widely used in:
- Registers
- Counters
- Memory devices
- Shift registers
- Digital communication systems

## Objective
To design and verify a positive-edge triggered D Flip-Flop using Verilog HDL.

## Truth Table

| Clock Edge | D | Q(next) |
|------------|---|---------|
| Rising Edge | 0 | 0 |
| Rising Edge | 1 | 1 |

## Tools Used
- Verilog HDL
- ModelSim / Vivado / Xilinx ISE
- GitHub

## Project Files
1. d_flipflop.v
2. d_flipflop_tb.v
3. Simulation Screenshot
4. README.md

## Working Principle
At every positive edge of the clock:
- If D = 0, Q becomes 0.
- If D = 1, Q becomes 1.

The output remains unchanged until the next clock edge.

## Applications
- Data storage
- Shift registers
- Counters
- Synchronizers
- State machines

## Expected Output
The output Q follows input D only at the positive edge of the clock.

## Author
Your Name