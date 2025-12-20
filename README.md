🔧 UART & Traffic Light Controller on FPGA

Structural VHDL | FSM-Based Digital Design

📘 Overview

FPGA-based UART and traffic light controller implemented using structural RTL design in VHDL.
The project emphasizes FSM-driven control logic, synchronous digital design, and verification through simulation and hardware testing.

Design Focus: Structural RTL design, FSM modeling, and simulation-driven verification

✨ Key Features

Structural VHDL (RTL-level design)

UART transmitter and receiver with 8× oversampling

Programmable baud rate generator

FSM-based UART control (polling-based)

Memory-mapped register interface

Hardware tested on Altera DE2 FPGA board

🧩 Architecture

Modular block-level design

Finite State Machines (FSMs) for:

UART transmit/receive control

Traffic light sequencing logic

Clear separation of control logic and datapath

🧪 Verification & Testing

Functional verification using ModelSim

Quartus waveform simulation and timing analysis

On-hardware validation on DE2 board

Consideration of metastability and clock-domain behavior

Analysis of discrepancies between simulation and hardware behavior

🛠 Tools & Technologies

VHDL (Structural RTL)

Finite State Machines (FSM)

Altera FPGA (DE2)

Quartus II
