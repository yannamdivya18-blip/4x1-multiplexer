# 4×1 Multiplexer using Verilog HDL

## Overview

This project implements a **4×1 Multiplexer (MUX)** using Verilog HDL.

A 4×1 multiplexer selects one of four input signals based on two select lines.

## Truth Table

| S1 | S0 | Output |
|----|----|--------|
| 0 | 0 | I0 |
| 0 | 1 | I1 |
| 1 | 0 | I2 |
| 1 | 1 | I3 |

---

## Project Structure

```
4x1-Multiplexer-Verilog
│
├── src/
│   └── mux4x1.v
├── tb/
│   └── mux4x1_tb.v
├── simulation/
│   ├── waveform.png
│   └── simulation_output.txt
└── README.md
```

---

## Simulation

Compile

```bash
iverilog -o mux mux4x1.v mux4x1_tb.v
```

Run

```bash
vvp mux
```

Generate waveform

```bash
gtkwave mux4x1.vcd
```

---

## Features

- Verilog HDL implementation
- Testbench included
- Waveform generation
- Simulation results
- Easy to run using Icarus Verilog

## Author

Your Name