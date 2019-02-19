

# Introduction

Malbolge is one of the most popular esoteric programming languages, named after the eighth circle of hell in Dante's Inferno, the
Malebolge.

Malbolge was specifically designed to hurt. It's almost impossible to use, because of crazy operation, self encrypting code and base-three arithmetic. It's way more difficult than other esoteric languages (such as Brainfuck), but takes this difficultness to the extreme. Despite this design, it is possible to write useful Malbolge programs. Malbolge is **not** Turing complete, there was attempt to create Turing complete variant of Malbolge, named Malbogle Unshackled.

Classic "Hello, world!" program looks bizzare in Malbolge:

```malbolge
(=<`#9]~6ZY32Vx/4Rs+0No-&Jk)"Fh}|Bcy?`=*z]Kw%oG4UUS0/@-ejc(:'8dc
```

Technically speaking, Malbolge is machine code for so called Malbolge Virtual Machine. It has three registers - `a`, `c`, and `d`. 
When a program starts, the value of all three registers is zero. It doesn't support stack and indefinite memory access out of the 
box either. The virtual machine has 59,049 memory locations that can each hold a ten-trit ternary number, making memory access 
limited consequently removing possibility of Turing completness. There were attempts to prove Malbolge Unshackled Turing 
completness. [Brainfuck interpreter in Malbolge Unshackled](https://github.com/KrzysztofSzewczyk/Brainfuck.MB) was written to do 
so. It can be proven using simulation way (which was described in Brainfuck chapter).

Malbolge is an amazingly difficult language. One needs still to understand where it would be more suitable, and where it doesn't
particularly excel at.


