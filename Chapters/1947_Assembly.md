# Assembly Language
## Introduction

Assembly language(or an assembler) is a low-level programming language which is the lowest abstraction of machine language(binary code). It consists of a strong but not one-one correspondence between its mnemonics and machine instructions supported. Unlike other high level programming languages, the Assembly Language is not completely portable in the sense that its syntax and semantics varies with the computer architecture(primarily) but the core concepts, essence and functioning remains the same.

## History
### Creation:
The first assembly language was developed by Kathleen Booth in 1947 for the ARC2 at  Birkbeck, University of London following work with John von Neumann and Herman Goldstine at the Institute for Advanced Study. After this several other variations of assembly language have been developed and higher abstractions of the language have been achieved.

### Purpose:
Back in the day it was extremely tedious,error prone and time consuming for programmers to "code" in binary. Even the smallest of the tasks required huge amount of thinking and calculations. Building huge programs then was a mammoth task. So the assembly languages have been created to get rid of the "tedious" part of coding in binary and to help concentrate more on the problem on hand rather than silly calculations and other laborious tasks.

## What it solves?
Consider an example instruction (program) where we have to add the two numbers 1 and 2 say.

**Assembly:**
>    
    addi x5 x0 1
    addi x6 x0 2
    add x7 x5 x6
---
**Binary:**
>00000000000100101000000000010011000000000010 001100000000000100110000000001110010100000110 1100011
 ---
**Binary in human readable format:**
>   0000000 00001 00101 000 00000 0010011    
    0000000 00010 00110 000 00000 0010011      
    0000000 00111 00101 000 00110 1100011

*This is same binary code with a single bit change. Happy debugging* :)
>00000000000100101000000000010011000000000010 001100000000000100110000000001100010100000110 1100011

**The architecture used in the above examples is RISC-V (32 bit).**

The purpose of an assembly language can easily be observed with the help of the above example. Assembly language with the help of its mnemonics makes it easier to code and not worry about trivial tasks such as opcodes, address calculations, etc. Mistakes if any can easily identified in assembly rather than in binary. Imagine finding such mistakes in a pool of 0's and 1's!

## Where would you use it?
In recent times programming in assembly is rare because automated programs exist(assemblers) which convert higher level languages into assembly and subsequently into machine language. Since there exists a strong correspondence between machine code and assembly mnemonics it can be used in applications where speed and performance is of importance but the application itself occupies minimal space.
> Computers powering earlier Apollo missions were programmed in assembly but the entire code was if written in a book would be about 5 feet in height.

Some places where direct programming assembly language can be used:

* To build software which requires  serious machine level optimizations or to beat compilers in code optimization. For eg: some system software in an OS (not needed though as modern compilers do a pretty good job).

* In embedded programming where space is limited to an extent that higher level languages (like C) and an assembler/compiler cannot included in storage.

* To access hardware specific features  which are either platform specific or too uncommon and not available for optimization in higher languages such as C.

* Written for custom hardware that don't have a mechanism to convert high level code into binary. The Appollo-11 Lunar mission is a good example as it was powered by programs written in assembly in  an era where high level languages did not exist.

## Shortcomings
Consider the same example in a previous section to add two number say 1 and 2 but written in C, a high level language.

>     #include<stdio.h>
      int main()
      {
          int x = 1;
          int y = 2;
          int z = x+y;
          return 0;
      }

As the reader might have observed coding in C turns out to be much more easier than assembly because each line of code is much more intuitive compared to either assembly or binary.

There is a trade-off between the incredible performance offered by assembly language and it being "programmer friendly"

* Coding in assembly sometimes is not intuitive and requires minute understanding compared to higher level languages such as C where the programmers literally write what they want to do.(refer the example)

* The entire code in assembly language could turn out to be monstrous in at some stage cannot be handled or maintained easily.

* Manually writing in assembly language for large programs such as an OS for instance can be frustrating (refer above point)

* Comparable performance of manually written assembly programs and programs written in higher level languages which are then translated into machine code using compilers, interpreters or similar mechanisms.

### Birth of higher level languages:
Even though assembly language offers high performance it cannot be effectively used to build user applications and even higher abstractions are necessary to do so. Also it is not completely "programmer friendly" in the sense that it is still a low level language and can be difficult to grasp or understand easily. Hence a need for abstracting assembly language itself arises which is both understandable and has the performance of assembly.

From this need were born higher level assembly languages which were a tad more "human friendly" than the initial low level assembly languages but they still remain assembly languages.

Afterwards even higher level languages were introduced which acted like an abstraction of assembly language itself. One of the most notable languages among these is C.

## A final word
Assembly language is a big leap from machine code towards higher level languages but like any other programming language assembly also has its own set of merits and demerits.

The reader might wonder why only C was used as a comparison. The reason is C is one of the few high level languages that offers similar speed and performance as assembly or other low level languages and is also highly portable.

## Sources and reference
- [Quora](https://www.quora.com/Why-is-Assembly-Language-used)
- [Wikipedia](https://en.wikipedia.org/wiki/Assembly_language)
- [Apollo-11 Guidance computer source code](https://github.com/chrislgarry/Apollo-11)
- [RISC-V opcodes](https://github.com/riscv/riscv-opcodes/blob/master/opcodes)
