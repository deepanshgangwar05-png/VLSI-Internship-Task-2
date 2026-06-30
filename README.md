# VLSI Internship Task-2
## Introduction
This repository contains Verilog HDL Implementations of Basic Combinational circuits using Xilinx ISE Design Suite.
The Project includes Verilog Coding , Testbench Creation , Simulation , Waveform Analysis and GitHub Documentaion.
## Objective
- Learn Verilog HDL fundamentals
- Understand RTL design concepts
- Implement combinational logic circuits
- Write Verilog testbenches
- Perform behavioral simulation
- Analyze waveform outputs
## Implemented Circuits
- AND Gate
- OR Gate
- NOT Gate
- NAND Gate
- NOR Gate
- XOR Gate
- Half Adder
- Full Adder
## Truth Table (Half Adder)
| A | B | SUM | CARRY |
|---|---|-----|-------|
| 0 | 0 |  0  |   0   |
| 0 | 1 |  1  |   0   |
| 1 | 0 |  1  |   0   |
| 1 | 1 |  0  |   1   |
## Truth Table (Full Adder)
| A | B | Cin | SUM | CARRY |
|---|---|-----|-----|-------|
| 0 | 0 |  0  |  0  |   0   |
| 0 | 0 |  1  |  1  |   0   |
| 0 | 1 |  0  |  1  |   0   |
| 0 | 1 |  1  |  0  |   1   |
| 1 | 0 |  0  |  1  |   0   |
| 1 | 0 |  1  |  0  |   1   |
| 1 | 1 |  0  |  0  |   1   |
| 1 | 1 |  1  |  1  |   1   |
## Sample Verilog Code 

```verilog
module half_adder(
    input A,
    input B,
    output SUM,
    output CARRY
);

assign SUM = A ^ B;
assign CARRY = A & B;

endmodule
```
## Tools Used
- Verilog HDL
- Xilinx ISE Design Suite
- ISim Simulator
- GitHub
## Simulation
Behavioral simulations were performed using ISim Simulator in Xilinx ISE Design Suite.
Waveforms were analyzed to verify correct output functionality.
# Screenshots
## All Logic Gates Output
<img width="1364" height="728" alt="IMG_20260630_152651 jpg" src="https://github.com/user-attachments/assets/7cd68ed7-e3b9-4a90-9a3d-b3a90957b0a8" />

## Half Adder Output

<img width="1364" height="728" alt="IMG_20260630_152803 jpg" src="https://github.com/user-attachments/assets/84838541-e8d8-4421-9f2a-8f011b1bbeda"/>
    
## Full Adder Output

<img width="1364" height="728" alt="IMG_20260630_152858 jpg" src="https://github.com/user-attachments/assets/8c4b7dae-7339-4a9d-bdac-de4e5ca6373b" />

## Learning Outcomes
- Learned Verilog HDL syntax and module design
- Understood combinational circuit implementation
- Gained experience in testbench writing
- Performed waveform analysis and simulation
- Improved GitHub project documentation skills
## Conclusion
This task provided practical exposure to digital logic design and Verilog HDL implementation.
The project improved understanding of RTL design flow, simulation techniques, and waveform verification used in VLSI front-end design.
## Author
DEEPANSH GANGWAR




