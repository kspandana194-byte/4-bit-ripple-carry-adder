4-Bit Ripple Carry Adder

Description

A 4-bit Ripple Carry Adder is a digital circuit that adds two 4-bit binary numbers. It is constructed using four full adders, where the carry output of each stage is connected to the carry input of the next stage.

Features

- Adds two 4-bit binary numbers
- Uses four full adders
- Produces a 4-bit sum
- Produces a final carry output
- Designed using Verilog HDL

Inputs

- "A[3:0]" – First 4-bit binary number
- "B[3:0]" – Second 4-bit binary number
- "Cin" – Initial carry input

Outputs

- "Sum[3:0]" – 4-bit addition result
- "Cout" – Final carry output

Working

The first full adder adds the least significant bits of A and B along with Cin. Its carry is passed to the next full adder. This process continues through all four stages, so the carry "ripples" from the LSB to the MSB.

Files

- "full_adder.v" – Verilog code for a full adder
- "ripple_carry_adder_4bit.v" – Main 4-bit RCA design
- "ripple_carry_adder_4bit_tb.v" – Testbench for verification
- "simulation_output.txt" – Example simulation results

Example

A = 1010
B = 0101
Cin = 0

Result:

Sum = 1111
Cout = 0

Applications

- Arithmetic Logic Units (ALUs)
- Digital processors
- Calculators
- Binary arithmetic circuits
- Computer systems

Tools

- Verilog HDL
- Icarus Verilog / ModelSim / Vivado
- GTKWave for waveform viewing

Author

Digital Electronics Project – 4-Bit Ripple Carry Adder
author spandana 
