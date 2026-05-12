# Microprocessor
This repository contains assembly language programs written for the 8086 Microprocessor using NASM (Netwide Assembler) as part of my Microprocessor Laboratory work.

About
The 8086 microprocessor is a 16-bit microprocessor designed by Intel. These programs are developed to understand fundamental concepts like data movement, arithmetic operations, logical operations, loops, and memory handling using Assembly language.

Tools and Software Used
Assembler: NASM (Netwide Assembler)

Emulator: DOSBox / any x86 emulator supporting 16-bit real mode

How to Run
Install NASM on your system.

Open the terminal/command prompt.

Assemble the code using NASM.

Link the object file to create an executable.

Run the executable in DOSBox or a 16-bit compatible environment.

Example commands:

bash
Copy
Edit
nasm -f bin filename.asm -o filename.com
Then run filename.com inside DOSBox.

If you're assembling .asm to .obj:

bash
Copy
Edit
nasm -f obj filename.asm
Then link it using a linker like alink, ld, or tlink.

Folder Structure
cpp
Copy
Edit
/
├──Experiment1.asm
├── Experiment2.asm
├── Experiment3.asm
├── ...
└── README.md
Author
Shravani Talwar
