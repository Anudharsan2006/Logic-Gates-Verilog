# Verilog Logic Gates

This repository contains Verilog HDL implementations of the seven basic logic gates along with individual testbenches for simulation.

## Included Gates

- AND Gate
- OR Gate
- NOT Gate
- NAND Gate
- NOR Gate
- XOR Gate
- XNOR Gate

## Project Structure

```
Verilog-Logic-Gates/
│
├── and_gate.v
├── or_gate.v
├── not_gate.v
├── nand_gate.v
├── nor_gate.v
├── xor_gate.v
├── xnor_gate.v
│
├── tb_and_gate.v
├── tb_or_gate.v
├── tb_not_gate.v
├── tb_nand_gate.v
├── tb_nor_gate.v
├── tb_xor_gate.v
├── tb_xnor_gate.v
│
└── README.md
```

## How to Simulate

### Using Icarus Verilog

Compile and run the AND gate example:

```bash
iverilog -o and_sim and_gate.v tb_and_gate.v
vvp and_sim
```

### Using Vivado / ModelSim

1. Create a new simulation project.
2. Add the gate module and corresponding testbench.
3. Run behavioral simulation.
4. Observe the waveform or console output.

## Truth Table Example (AND Gate)

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

## Learning Outcomes

This project demonstrates:

- Basic RTL coding in Verilog
- Combinational logic design
- Module instantiation
- Writing simple testbenches
- Digital simulation workflow

## Author

**Anudharsan R R**  
B.E. Electronics  Engineering (VLSI Design and Technology)  
FPGA &amp; VLSI Enthusiast
