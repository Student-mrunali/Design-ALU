COMPANY : CODETECH IT SOLUTION
NAME : MRUNALI KALE
INTERN ID : CT08JPQ
DOMAIN : VLSI
DURATION : 4 WEEKS
MENTOR : SRAVANI
TASK NAME: DESIGN ALU USING VERILOG
DESCRIPTION :
Step 1: Define the ALU Functional Requirements
Inputs:
Two N-bit operands: A and B
A control signal (select) to choose the operation

Operations:
000 → Addition (A + B)
001 → Subtraction (A - B)
010 → Bitwise AND (A & B)
011 → Bitwise OR (A | B)
100 → Bitwise XOR (A ^ B)
101 → Left Shift (A << 1)
110 → Right Shift (A >> 1)
111 → Multiplication (A * B)

Outputs:
N-bit result (Result)
A Zero flag (1 if Result is zero)

Simulate and Verify Output
Run the testbench in a Verilog simulator (ModelSim, Xilinx Vivado, or Quartus).
Check that each select value produces the expected Result.
Verify that the Zero flag is set correctly.
