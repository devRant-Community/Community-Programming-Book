# Assembly Language
---
## Introduction

Assembly language(or an assembler) is a low-level programming language which is the lowest abstraction of machine language(binary code). Unlike other high level programming languages, the Assembly Language is not completely portable in the sense that its syntax and semantics varies with the computer architecture(primarily) but the core concepts, essence and functioning remains the same.
## History
---
### Creation:
The first assembly language was developed by Kathleen Booth in 1947 for the ARC2 at  Birkbeck, University of London following work with John von Neumann and Herman Goldstine at the Institute for Advanced Study. After this several other variations of assembly language have been developed and higher abstractions of the language have been achieved.

### Purpose:
Back in the day it was extremely tedious,error prone and time consuming for programmers to "code" in binary. Even the smallest of the tasks required huge amount of thinking and calculations. Building huge programs then was a mammoth task. So the assembly languages have been created to get rid of the "tedious" part of coding in binary and to help concentrate more on the problem on hand rather than silly calculations and other laborious tasks.
## What it solves?
Consider an example program where we have to add two numbers stored in a register with address 5 and 6 and then store the resultant in the register with address 7 say. **The computer architecture here is 32 bit RISC-V hence both examples correspond to this architecture**
>    add x7 x5 x6
---
> 00000000011100101000001101100011

---
This is same binary code with a mistake. Happy debugging :)
> 00000000011100101000001101000011

The purpose of an assembly language can easily be observed with the help of the above example. Assembly language with the help of its mnemonics makes it easier to code and not worry about trivial tasks such as opcodes, address calculations, etc. Also mistakes if any can easily identified in assembly rather than in binary. Imagine finding such mistakes in a pool of 0's and 1's!
## Where would you use it?
In recent times programming in assembly is rare because automated programs exist(assemblers) which convert higher level languages into assembly and subsequently into machine language. Since there exists a strong correspondence between machine code and assembly mnemonics it can be used in applications where speed and performance is of importance.
> Computers powering earlier Apollo missions were programmed in assembly but the book containing the entire code was about 5 feet in height.

## Shortcomings
As mentioned in the previous section the entire code in assembly language could turn out to be monstrous in at some stage cannot be handled. Manually writing in assembly language for large programs such as an OS for instance can be less frustrating than writing in binary but frustrating neverthless. In modern times coding in assembly is out of the question.   
