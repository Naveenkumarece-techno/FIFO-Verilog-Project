# FIFO-Verilog-Project
Designed a synchronous FIFO memory using Verilog HDL for efficient temporary data storage and transfer. Implemented read/write pointer logic, full/empty flag generation, and synchronous control. Verified functionality using RTL simulation and waveform analysis.
# Synchronous FIFO Memory using Verilog HDL

## 📌 Overview
This project implements a Synchronous FIFO (First-In First-Out) memory using Verilog HDL for efficient temporary data storage and controlled data transfer in digital systems.

The design follows RTL methodology and uses clock-synchronous read/write operations with proper pointer management and status flag generation.

---

## ⚙️ Features
- FIFO memory design using Verilog HDL
- Synchronous read and write operations
- Read/Write pointer logic
- Full and Empty flag generation
- Reset and clock-based control
- RTL design methodology

---

## 🧠 Working Principle
Data is written into memory sequentially and read in the same order (FIFO principle).  
Read and write pointers track memory locations, while full and empty flags indicate buffer status.

---

## 🛠️ Tools Used
- Verilog HDL
- Xilinx Vivado / ModelSim
- RTL Simulation
---

## 🧪 RTL Design
The FIFO module is designed using Verilog HDL with:
- Parameterized memory depth (optional)
- Synchronous reset
- Read/write enable control
- Pointer-based addressing system

---

## 🔬 Testbench
The testbench verifies:
- Data write and read operations
- FIFO full condition
- FIFO empty condition
- Correct sequencing of data flow

---

## 📊 Simulation
Behavioral simulation was performed using ModelSim / Vivado.  
Waveforms confirm correct FIFO behavior including proper data ordering and flag generation.

---

## 🚀 Learning Outcomes
- FIFO architecture understanding
- Pointer-based memory design
- RTL simulation and debugging
- Digital system verification flow

---

## 👨‍💻 Author
Naveen Kumar
