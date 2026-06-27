# 4-Bit-Processor
A complete 4-bit processor designed from scratch using Digital Logic Design principles, capable of executing arithmetic, logical, data transfer, and shift operations through a custom 7-bit instruction set. <br>
📌 Overview <br>

This project demonstrates the design and implementation of a 4-bit processor capable of interpreting and executing instructions through a 7-bit instruction format. The processor integrates register architecture, instruction decoding, control logic, and an Arithmetic Logic Unit (ALU) to simulate how a basic CPU processes instructions at the hardware level.<br>

Built entirely using Digital Logic Design concepts, this project provides a practical understanding of processor organization, instruction execution, register operations, and data flow within a processor. <br>
✨ Features <br>
🧠 Custom 7-bit Instruction Set Architecture (ISA) <br>
📦 Four 4-bit General Purpose Registers<br>
📝 Dedicated Instruction Register (IR)<br>
⚙️ Arithmetic Logic Unit (ALU)<br>
🔍 Instruction Decoding using a 3×8 Decoder<br>
🎯 Register Selection using 2×4 Decoders<br>
💾 Register implementation using D Flip-Flops<br>
🔀 Data Routing using 8×1 Multiplexers<br>
⏱️ Clock-Synchronized Operation<br>
🧩 Modular Hardware Design<br>

🚀 Supported Instructions<br>
Opcode     Operation	   Description<br>
LOAD       Load external   4-bit data into a register<br>
MOV	       Transfer data between registers<br>
ADD        Perform binary addition<br>
SUB	       Perform binary subtraction<br>
MUL	       Multiply two 4-bit numbers (8-bit output)<br>
OR	       Bitwise OR operation<br>
SHL        Shift Left (Multiply by 2ⁱ)<br>
SHR	       Shift Right (Divide by 2ⁱ)<br>

🏗️ Processor Architecture<br>

The processor consists of the following major components:<br>

Instruction Register (IR)<br>
Four 4-bit Registers<br>
3×8 Opcode Decoder<br>
2×4 Register Decoders<br>
Arithmetic Logic Unit (ALU)<br>
Multiplexers<br>
Control Logic<br>
Clock-Controlled Sequential Circuitry<br>

Together, these components perform the complete Fetch → Decode → Execute cycle for every instruction.<br>

⚙️ Instruction Format<br>

Each instruction is 7 bits long.<br>

┌──────────┬──────────┬──────────┐<br>
│ Opcode   │ Register │ Register │<br>
│ 3 Bits   │ R1 (2)   │ R2 (2)   │<br>
└──────────┴──────────┴──────────┘<br>
Opcode → Selects the operation<br>
R1 → Destination Register<br>
R2 → Source Register<br>

# Digital Logic Concepts Used<br>
D Flip-Flops<br>
Multiplexer<br>
Decoders<br>
Register Design<br>
Sequential Logic<br>
Combinational Logic<br>
Ripple Carry Adder<br>
Two's Complement Subtractor<br>
Binary Multiplier<br>
Shift Registers<br>
ALU Design<br>
Control Logic<br>
Clock Synchronization<br>

📈 Experimental Results<br>

The processor successfully executed all supported instructions with accurate outputs.<br>

✔ Load Operation<br>

✔ Register Transfer<br>

✔ Binary Addition<br>

✔ Binary Subtraction<br>

✔ Binary Multiplication<br>

✔ Logical OR<br>

✔ Shift Left<br>

✔ Shift Right<br>

📌 Future Improvements<br>

Possible extensions include:<br>

Upgrade from 4-bit to 8-bit/16-bit Processor<br>
Additional ALU Operations (AND, XOR, NOT)<br>
More General Purpose Registers<br>
Status Flags (Carry, Zero, Overflow)<br>
Memory Interface<br>
Program Counter<br>
Instruction Pipeline<br>
Enhanced Control Unit<br>


👥 Team<br>
Hadia Noor<br>
Tooba Azam<br>
Mahrukh Mehboob<br>


This project bridges the gap between theoretical Digital Logic Design and real processor architecture by demonstrating how instructions are decoded, executed, and stored inside a simple CPU. It serves as a strong foundation for understanding modern computer architecture and hardware system design.