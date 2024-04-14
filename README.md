# Vedic Multiplication Verilog

This Verilog project implements a Vedic multiplier for multiplying two 8-bit numbers. Vedic multiplication is a technique derived from ancient Indian mathematics, which uses various mathematical principles to efficiently perform multiplication.

The project consists of several modules:

1. Half Adder (`ha`): Performs half addition, computing the sum and carry of two input bits.
2. Adders for different bit widths (`add_4_bit`, `add_6_bit`, `add_8_bit`, `add_12_bit`): Performs addition for 4-bit, 6-bit, 8-bit, and 12-bit inputs respectively.
3. Vedic multiplier modules (`vedic_2_x_2`, `vedic_4_x_4`, `vedic_8X8`): These modules implement the Vedic multiplication algorithm for multiplying 2x2, 4x4, and 8x8 bit numbers respectively.

The `test_vedic_8` module serves as the testbench. It provides stimulus to the Vedic multiplier by applying various input values to `a` and `b`, and monitors the output `c` for verification.

In summary, this project demonstrates the implementation and testing of a Vedic multiplier for multiplying two 8-bit numbers efficiently using Verilog HDL.
