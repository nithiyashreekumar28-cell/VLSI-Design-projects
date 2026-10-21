# Half Adder Using Verilog HDL

## 1. Project Overview
This project implements a Half Adder circuit using Verilog Hardware Description Language (HDL). The design is verified using a testbench and can be simulated using an online simulator.

## 2. Objective
To design and verify a combinational logic circuit that adds two single-bit binary inputs.

## 3. Inputs
- A: First binary input
- B: Second binary input

## 4. Outputs
- SUM: Sum output calculated using XOR logic
- CARRY: Carry output calculated using AND logic

## 5. Tools Used
- Verilog HDL
- EDA Playground
- GitHub

## 6. Project Files
- `half_adder.v` — Verilog design module
- `half_adder_tb.v` — Testbench for simulation
- `README.md` — Project documentation

## 7. Simulation Procedure
1. Open https://edaplayground.com/
2. Select Verilog for the design and testbench languages.
3. Paste the design code into the Design editor.
4. Paste the testbench into the Testbench editor.
5. Select an available simulator and click Run.
6. Verify the outputs against the truth table.

## 8. Truth Table

| A | B | SUM | CARRY |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

## 9. Conclusion
The Half Adder demonstrates basic binary addition using combinational logic and Verilog HDL. The project provides a foundation for further digital design and VLSI learning.
