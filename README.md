# Single-Cycle-RV32I
A complete 32-bit RV32I RISC-V processor designed and implemented in Verilog HDL, featuring RTL architecture. The project includes functional simulation and verification using testbenches, successful deployment on the Basys3 FPGA board for real-time hardware validation through execution of program of Fibonacci sequence.
# RISC-V Processor Implementation on Basys3 FPGA

A complete implementation of a **32-bit RISC-V processor written in Verilog**, designed from scratch and deployed on the **Basys3 (Artix-7) FPGA board**.  
The processor executes a **Fibonacci sequence program stored in instruction memory**, demonstrating correct instruction decoding, ALU operations, register file interactions, and program control flow.

The design includes a **clock divider to convert the 100 MHz Basys3 clock to a slower clock**, allowing visible step-by-step execution of instructions and easier hardware verification.

The processor design was **fully simulated, synthesized, and verified on real FPGA hardware**.

---

# Project Overview
This project implements a **single-cycle 32-bit RISC-V processor** based on the RV32I base integer instruction set architecture. The design includes all major datapath and control components required for instruction fetch, decode, execution, memory access, and write-back operations.
The processor was:
- Designed using Verilog HDL
- Simulated and verified using Icarus Verilog and GTKWave
- Synthesized and deployed on the Basys3 FPGA board
- Tested with assembly programs for functional verification
- The processor supports essential arithmetic and control instructions and successfully executes a **Fibonacci program** loaded into instruction memory.

The system was implemented and verified using **Xilinx Vivado** and tested on the **Basys3 FPGA development board**.

---

# Key Features

- 32-bit **RISC-V processor implementation**
- Single-cycle processor capable of executing**R-Type, I-Type, S-Type, B-Type, U-Type, and J-Type** instructions.
- Modular RTL design using **Verilog HDL**
- RTL modules including:
  - Program Counter
  - Instruction Fetch
  - Instruction Decode
  - Control Unit
  - Register File
  - Immediate Generator
  - ALU control unit
  - Memory Access
  - Write Back
  - PC Next
  - Processor
- **Clock divider** for Basys3 100 MHz system clock
- Execution of **Fibonacci program**
- Complete **simulation testbench**
- **XDC constraint file** for Basys3 board
- Successfully **synthesized and deployed on FPGA hardware**


