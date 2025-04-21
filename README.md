# 8-Bit CPU Simulation (Logisim)
This project is a simulation of a simple **8-bit CPU** built using **Logisim**. It includes core components such as an Arithmetic Logic Unit (ALU), a register file, a control unit, and a memory interface. The CPU is capable of executing basic instructions like **MOV**, **ADD**, **SUB**, **JMP**, and supports immediate values and memory operations.

# How to run

Open **Intellegent 404.circ** in **Logisim**

Load your machine code into the **Program ROM** inside the **Code Memory**.

Use the clock (manual or auto-tick) to step through execution and observe the behavior.

# Microcode / Control Logic

**Control signals** are generated using a **microcode ROM**.

Execution is broken into **micro-steps** based on the current instruction and timing.

You can view and modify the micro-instructions in the **Micro Operations ROM**.

There are 2 unused control signals, giving room to add new features or instructions.

# Instructions & Micro-Instructions

Instruction encoding and microcode mapping are documented in the included **Excel file**.

To add new instructions:

1. Define their **machine code** and place them in **Code Memory**.

2. Write corresponding **micro-instructions** in the **Micro Operations ROM**.

