# Sequence Detector using Mealy FSM (Verilog HDL)

## Description
This project implements a sequence detector using a Mealy Finite State Machine (FSM). The FSM detects the binary sequence "1011" from a serial input stream. In a Mealy machine, the output depends on both the present state and the input, enabling faster detection than a Moore FSM.

## Sequence Details
- Sequence: 1011
- FSM Type: Mealy
- Overlapping: Yes

## Inputs and Outputs

| Signal | Description |
|------|------------|
| clk | Clock input |
| rst_n | Active-low asynchronous reset |
| in | Serial input |
| out | Output (1 when sequence detected) |

## Operation
- FSM transitions occur on the rising edge of the clock
- Output is asserted immediately when the sequence is detected
- Reset initializes the FSM to the starting state

## Tools Used
- Verilog HDL
- ModelSim / Vivado / Icarus Verilog

## Author
Designed for academic and learning purposes.
