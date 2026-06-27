# 4-Bit-Processor
A complete 4-bit processor designed from scratch using Digital Logic Design principles, capable of executing arithmetic, logical, data transfer, and shift operations through a custom 7-bit instruction set. <br>
📌 Overview <br>

This project demonstrates the design and implementation of a 4-bit processor capable of interpreting and executing instructions through a 7-bit instruction format. The processor integrates register architecture, instruction decoding, control logic, and an Arithmetic Logic Unit (ALU) to simulate how a basic CPU processes instructions at the hardware level.<br>

Built entirely using Digital Logic Design concepts, this project provides a practical understanding of processor organization, instruction execution, register operations, and data flow within a processor. <br>
✨ Features
🧠 Custom 7-bit Instruction Set Architecture (ISA)
📦 Four 4-bit General Purpose Registers
📝 Dedicated Instruction Register (IR)
⚙️ Arithmetic Logic Unit (ALU)
🔍 Instruction Decoding using a 3×8 Decoder
🎯 Register Selection using 2×4 Decoders
💾 Register implementation using D Flip-Flops
🔀 Data Routing using 8×1 Multiplexers
⏱️ Clock-Synchronized Operation
🧩 Modular Hardware Design

🚀 Supported Instructions
Opcode     Operation	   Description
LOAD       Load external   4-bit data into a register
MOV	       Transfer data between registers
ADD        Perform binary addition
SUB	       Perform binary subtraction
MUL	       Multiply two 4-bit numbers (8-bit output)
OR	       Bitwise OR operation
SHL        Shift Left (Multiply by 2ⁱ)
SHR	       Shift Right (Divide by 2ⁱ)

🏗️ Processor Architecture

The processor consists of the following major components:

Instruction Register (IR)
Four 4-bit Registers
3×8 Opcode Decoder
2×4 Register Decoders
Arithmetic Logic Unit (ALU)
Multiplexers
Control Logic
Clock-Controlled Sequential Circuitry

Together, these components perform the complete Fetch → Decode → Execute cycle for every instruction.

⚙️ Instruction Format

Each instruction is 7 bits long.

┌──────────┬──────────┬──────────┐
│ Opcode   │ Register │ Register │
│ 3 Bits   │ R1 (2)   │ R2 (2)   │
└──────────┴──────────┴──────────┘
Opcode → Selects the operation
R1 → Destination Register
R2 → Source Register

# Digital Logic Concepts Used
D Flip-Flops
Multiplexers
Decoders
Register Design
Sequential Logic
Combinational Logic
Ripple Carry Adder
Two's Complement Subtractor
Binary Multiplier
Shift Registers
ALU Design
Control Logic
Clock Synchronization

📈 Experimental Results

The processor successfully executed all supported instructions with accurate outputs.

✔ Load Operation

✔ Register Transfer

✔ Binary Addition

✔ Binary Subtraction

✔ Binary Multiplication

✔ Logical OR

✔ Shift Left

✔ Shift Right

📌 Future Improvements

Possible extensions include:

Upgrade from 4-bit to 8-bit/16-bit Processor
Additional ALU Operations (AND, XOR, NOT)
More General Purpose Registers
Status Flags (Carry, Zero, Overflow)
Memory Interface
Program Counter
Instruction Pipeline
Enhanced Control Unit


👥 Team
Hadia Noor
Tooba Azam
Mahrukh Mehboob


This project bridges the gap between theoretical Digital Logic Design and real processor architecture by demonstrating how instructions are decoded, executed, and stored inside a simple CPU. It serves as a strong foundation for understanding modern computer architecture and hardware system design.