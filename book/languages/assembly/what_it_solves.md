# Why Assembly?

Consider an example instruction (program) where we have to add the two numbers 1 and 2 say.

**Assembly:**
>addi x5 x0 1
 addi x6 x0 2
 add x7 x5 x6
---
**Binary:**
>00000000000100101000000000010011000000000010 001100000000000100110000000001110010100000110 1100011
 ---
**Binary in human readable format:**
> 0000000 00001 00101 000 00000 0010011    
  0000000 00010 00110 000 00000 0010011      
  0000000 00111 00101 000 00110 1100011

*This is same binary code with a single bit change. Happy debugging* :)
>00000000000100101000000000010011000000000010 001100000000000100110000000001100010100000110 1100011

**The architecture used in the above examples is RISC-V (32 bit).**

The purpose of an assembly language can easily be observed with the help of the above example. Assembly language with the help of its mnemonics makes it easier to code and not worry about trivial tasks such as opcodes, address calculations, etc. Mistakes if any can easily identified in assembly
rather than in binary. Imagine finding such mistakes in a pool of 0's and 1's!
