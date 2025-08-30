# 📘 Computer Architecture

This repository contains my study notes on **Computer Architecture**.  
Each topic is written in both **Korean** and **English**, so I can study and review concepts in both languages.  

---

## 📑 Table of Contents

### 1. Computer System Organization (CPU, Memory, I/O, Bus)
- 📄 [Korean](./1.1-1_컴퓨터_시스템_구성.md) | 🌐 [English](./1.1-1_system_organization.md)  
- **CPU**: Responsible for computation and control (registers, ALU, control unit).  
- **Memory**: Stores programs and data (RAM, SSD/HDD).  
- **I/O Devices**: Interfaces with external environment (keyboard, NIC, etc.).  
- **Bus**: Data, address, and control buses connect CPU–Memory–I/O.  
- **Focus**: Understanding the data flow between CPU–Memory–I/O using block diagrams.  

---

### 2. Data Representation (Binary, Two’s Complement, IEEE 754)
- 📄 [Korean](./1.1-2_데이터_표현.md) | 🌐 [English](./1.1-2_Data_Representation.md)  
- **Binary**: Fundamental representation (0 and 1).  
- **Two’s Complement**: Negative number representation, simplifies addition/subtraction.  
- **IEEE 754**: Floating-point standard (sign, exponent, mantissa).  
- **Focus**: Decimal ↔ Binary conversion, two’s complement, IEEE 754 structure.  

---

### 3. CPU Operation (Registers, ALU, Control Unit)
- 📄 [Korean](./1.1-3_CPU_동작.md) | 🌐 [English](./1.1-3_CPU_Operation.md)  
- **Registers**: High-speed storage (PC, IR, MAR, MDR, Flag, etc.).  
- **ALU**: Performs arithmetic/logical operations, updates flags (ZF, CF, OF).  
- **Control Unit (CU)**: Decodes instructions, generates control signals, handles interrupts.  
- **Focus**: Roles of registers and internal CPU data flow.  

---

### 4. Instruction Format & Addressing Modes
- 📄 [Korean](./1.1-4_명령어형식&주소지정방식.md) | 🌐 [English](./1.1-4_Instruction_Format&Addressing_Modes.md)  
- **Instruction Format**: OpCode (operation) + Operand (data/address).  
- **Addressing Modes**: Immediate, Direct, Indirect, Register, Displacement, Stack.  
- **Focus**: How instructions locate and access operands for execution.  

---

### 5. Instruction Cycle (Fetch–Decode–Execute)
- 📄 [Korean](./1.1-5_명령어_사이클.md) | 🌐 [English](./1.1-5_Instruction_Cycle.md)  
- **Fetch**: Retrieve instruction from memory → IR.  
- **Decode**: CU interprets the instruction and generates control signals.  
- **Execute**: ALU operation, memory access, update registers/flags.  
- **Focus**: Step-by-step data flow, roles of PC, IR, ALU, and flags.  

---

### 6. Pipelining & Hazards
- 📄 [Korean](./1.1-6_파이프라이닝&해저드.md) | 🌐 [English](./1.1-6_Pipelining&Hazards.md)  
- **Pipelining**: Overlapping execution of multiple instructions to improve performance.  
- **Hazards**: Pipeline stalls caused by Data, Control, or Structural hazards.  
- **Solutions**: Forwarding, Stall, Branch Prediction, Resource Duplication.  
- **Advanced**: Superscalar, Out-of-Order Execution, Speculation, VLIW.  
- **Focus**: Pipeline structure and bottleneck resolution.  

---

### 7. CPU Performance Metrics & Instruction Set Architecture (RISC vs CISC)
- 📄 Korean file (coming soon) | 🌐 English file (coming soon)  
- **Performance Metrics**:  
  - CPU Time = Instruction Count × CPI × Clock Cycle Time  
  - IPC (Instructions Per Cycle), MIPS, etc.  
- **RISC vs CISC**:  
  - RISC: Simple instructions, hardwired control, high pipeline efficiency.  
  - CISC: Complex instructions, microprogrammed control, higher flexibility.  
- **Focus**: Comparing performance metrics and ISA design philosophy.  

---

### 8. Memory Hierarchy (Cache, Locality)
- 📄 Korean file (coming soon) | 🌐 English file (coming soon)  
- **Hierarchy**: Register → Cache → RAM → Secondary Storage.  
- **Locality**: Temporal and spatial locality.  
- **Focus**: Cache operation and performance optimization.  

---

### 9. Interrupts & DMA
- 📄 Korean file (coming soon) | 🌐 English file (coming soon)  
- **Interrupts**: CPU suspends current task to handle external events.  
- **DMA**: I/O device accesses memory directly to reduce CPU overhead.  
- **Focus**: Interrupt handling flow, benefits of DMA.  

---

### 10. Parallel Processing (SIMD, MIMD, GPU)
- 📄 Korean file (coming soon) | 🌐 English file (coming soon)  
- **SIMD**: Single instruction, multiple data (vector processing).  
- **MIMD**: Multiple instructions, multiple data (multicore CPUs).  
- **GPU**: Specialized for massive parallel computations.  
- **Focus**: Differences between SIMD vs MIMD, GPU strengths.  

---
