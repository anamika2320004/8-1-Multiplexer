# 8:1 Multiplexer (MUX) Verilog Project

## Project Overview
This project demonstrates an **8:1 Multiplexer (MUX)** implemented in Verilog. A multiplexer selects one of the 8 input signals and forwards it to a single output line based on the value of a 3-bit select line.

**Learning Outcomes:**
- Conditional selection in Verilog
- Understanding 3-bit select lines
- Module reuse for larger digital designs

## Circuit Description
- **Inputs:**
  - `d[7:0]` : 8-bit data input (d0 to d7)
  - `sel[2:0]` : 3-bit select line to choose one input
- **Output:**
  - `y` : Output corresponding to the selected input

**Truth Table:**

| sel   | Output (y) |
|-------|------------|
| 000   | d0         |
| 001   | d1         |
| 010   | d2         |
| 011   | d3         |
| 100   | d4         |
| 101   | d5         |
| 110   | d6         |
| 111   | d7         |

## Files Included
- `txt file` : 8:1 Multiplexer module and testbench


## Simulation
The testbench cycles through all select line values and displays the corresponding output.  
Run the simulation in **EDA Playground** or any Verilog simulator.

**Example Output:**
sel=000, y=1
sel=001, y=1
sel=010, y=0
sel=011, y=1
sel=100, y=0
sel=101, y=1
sel=110, y=1
sel=111, y=1

## How to Run
1. Open `txt file for code and testbench` in EDA Playground or a Verilog simulator.
2. Run the simulation.
3. Observe the console output to verify correct multiplexer behavior.

