This repository was used to get ready for the Laboratory part of the 2022 edition of the Formal Languages and Compiler course at Politecnico di Milano.
The laboratory part requires students to add language features to a compiler. For each exam session, a different feature is introduced.

ACSE (Advanced Compiler System for Education) introduces students to Compilers programming. This toolchain includes three main components:
 - compiler to assembly (acse)
 - assembler to machine code (asm)
 - interpreter (mace)

The goal is to introduce new features to the language that ACSE accepts, in the form of new expressions or statements. ACSE codebase is modified 
and used to compile C-like code. The interpreter takes the output of the assembler to run the newly generated RISC-like machine code.

Each branch represents a different feature that was requested at a given exam session. The 'main' branch presents the original unmodified ACSE source code.
