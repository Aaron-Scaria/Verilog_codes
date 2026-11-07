# Verilog_codes
# 4:1 Multiplexer Design Using Verilog

## 1. Overview
This project implements a 4:1 Multiplexer (MUX) using Verilog HDL.

A 4:1 multiplexer selects one of four input signals based on the two-bit select line and forwards the selected input to the output.

## 2. Design Details

- **Inputs:** 4 data inputs (I0, I1, I2, I3)
- **Select Lines:** 2-bit select (S1, S0)
- **Output:** 1-bit output (Y)

### Truth Table

| S1 | S0 | Output |
|---|---|---|
| 0 | 0 | I0 |
| 0 | 1 | I1 |
| 1 | 0 | I2 |
| 1 | 1 | I3 |

## 3. Project Files

| File | Description |
|---|---|
| `mux_4_1.v` | RTL design of the 4:1 multiplexer |
| `mux_4_1_tb.v` | Testbench for functional verification |

## 4. Simulation

- **HDL:** Verilog
- **Simulation Tool:** ModelSim

The testbench applies different input combinations and select-line values to verify the functionality of the multiplexer.

## 5. Verification

The design is verified by simulating the RTL module using the testbench and checking whether the output matches the selected input.

## 6. Concepts Demonstrated

- Combinational logic design
- Multiplexer functionality
- Verilog HDL
- RTL design
- Testbench development
- Functional simulation
