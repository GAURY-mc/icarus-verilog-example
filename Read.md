# Verilog Simulation with Icarus Verilog

This project contains a simple logic circuit (`example.v`) and a testbench (`example-test.v`) simulated using Icarus Verilog and GTKWave.

## How to Run

1. Compile:
iverilog -o mysim.vvp example.v example-test.v


2. Simulate:
vvp mysim.vvp


3. View Waveform:
gtkwave example.vcd

## Tools Used

- Icarus Verilog
- GTKWave
