# 📘 Computer Architecture

This repository contains my study notes on **Computer Architecture**.  
Each topic is written in both **Korean** and **English**, so I can study and review concepts in both languages.  

---

## 📑 Table of Contents

### 1. Computer System Organization (CPU, Memory, I/O, Bus)
- 📄 [Korean](./1.1-1_컴퓨터_시스템_구성.md) | 🌐 [English](./1.1-1_system_organization.mdd)  
- **CPU**: Computation and control (Registers, ALU, Control Unit).  
- **Memory**: Stores programs and data (RAM, SSD/HDD).  
- **I/O Devices**: Interfaces with the outside world (Keyboard, NIC, etc.).  
- **Bus**: Data, address, and control buses connect CPU–Memory–I/O.  
- **Focus**: Understanding CPU–Memory–I/O data flow with block diagrams.  

---

### 2. Data Representation (Binary, Two’s Complement, IEEE 754)
- 📄 [Korean](./1.1-2_데이터_표현.md) | 🌐 [English](./1.1-2_Data_Representation.md)  
- **Binary**: Fundamental representation (0 and 1).  
- **Two’s Complement**: Negative number representation for simpler arithmetic.  
- **IEEE 754**: Floating-point standard (Sign, Exponent, Mantissa).  
- **Focus**: Decimal ↔ Binary conversion, two’s complement, IEEE 754 structure.  

---

### 3. CPU Operation (Registers, ALU, Control Unit)
- 📄 [Korean](./1.1-3_CPU_동작.md) | 🌐 [English](./1.1-3_CPU_Operation.md)  
- **Registers**: High-speed storage (PC, IR, MAR, MDR, Flags).  
- **ALU**: Performs arithmetic/logical operations, updates flags (ZF, CF, OF).  
- **Control Unit (CU)**: Decodes instructions, generates signals, handles interrupts.  
- **Focus**: Roles of registers and internal CPU data movement.  

---

### 4. Instruction Format & Addressing Modes
- 📄 [Korean](./1.1-4_명령어형식&주소지정방식.md) | 🌐 [English](./1.1-4_Instruction_Format&Addressing_Modes.md)  
- **Instruction Format**: OpCode (operation) + Operand (data/address).  
- **Addressing Modes**: Immediate, Direct, Indirect, Register, Displacement, Stack.  
- **Focus**: How instructions locate and access operands.  

---

### 5. Instruction Cycle (Fetch–Decode–Execute)
- 📄 [Korean](./1.1-5_명령어_사이클.md) | 🌐 [English](./1.1-5_Instruction_Cycle.md)  
- **Fetch**: Instruction fetched into IR.  
- **Decode**: CU interprets and generates control signals.  
- **Execute**: ALU operations, memory access, register updates.  
- **Focus**: Step-by-step data flow, roles of PC, IR, ALU, Flags.  

---

### 6. Pipelining & Hazards
- 📄 [Korean](./1.1-6_파이프라이닝&해저드.md) | 🌐 [English](./1.1-6_Pipelining&Hazards.md)  
- **Pipelining**: Overlap execution of multiple instructions.  
- **Hazards**: Data, Control, Structural hazards.  
- **Solutions**: Forwarding, Stall, Branch Prediction.  
- **Advanced**: Superscalar, Out-of-Order Execution, Speculation, VLIW.  
- **Focus**: Pipeline structure and bottleneck resolution.  

---

### 7. CPU Performance Metrics & ISA (RISC vs CISC)
- 📄 [Korean](./1.1-7_CPU_성능&ISA.md) | 🌐 [English](./1.1-7_CPU_performance&ISA.md)  
- **Performance Metrics**:  
  - CPU Time = Instruction Count × CPI × Clock Cycle Time  
  - IPC, MIPS, etc.  
- **RISC vs CISC**:  
  - RISC: Simple instructions, hardwired control, high pipeline efficiency.  
  - CISC: Complex instructions, microprogrammed control, more flexible.  
- **Also Covers**: Multithreading, Multiprocessing, Hyper-Threading.  
- **Focus**: Comparing performance metrics and ISA design philosophies.  

---

### 8. Memory Hierarchy (Cache, Locality, Mapping, Replacement, Write Policies)
- 📄 [Korean](./1.1-8_메모리계층.md) | 🌐 [English](./1.1-8_Memory_Hierarchy.md)  
- **Hierarchy**: Register → Cache → RAM → Secondary Storage.  
- **Locality**: Temporal & Spatial locality.  
- **Cache Mapping**: Direct, Fully Associative, Set-Associative.  
- **Replacement Policies**: LRU, FIFO, Random.  
- **Write Policies**: Write-through, Write-back (Dirty bit).  
- **Focus**: Cache operation, performance optimization, and locality-based coding practices.  

---

### 9. Interrupts & DMA (with I/O Techniques)
- 📄 [Korean](./1.1-9_인터럽트&DMA.md) | 🌐 [English](./1.1-9_Interrupts&DMA.md)  
- **Interrupts**: CPU suspends current task to handle events.  
- **DMA**: I/O devices directly access memory to reduce CPU load.  
- **I/O Control Methods**: Programmed I/O, Interrupt-driven I/O, DMA.  
- **Buffering & Spooling**: Handling speed mismatch between CPU and devices.  
- **Focus**: Interrupt flow, DMA benefits, efficient I/O management.  

---

### 10. Parallel Processing & Performance Laws
- 📄 [Korean](./1.1-10_병렬_처리.md) | 🌐 [English](./1.1-10_Parallel_Processing.md)  
- **SIMD**: Single instruction, multiple data.  
- **MIMD**: Multiple instructions, multiple data.  
- **GPU**: Specialized for massive parallel workloads.  
- **Performance Laws**:  
  - Amdahl’s Law (parallelization limits).  
  - Gustafson’s Law (scalability with workload size).  
- **Focus**: Parallel architectures, GPU strength, laws of parallel speedup.  
