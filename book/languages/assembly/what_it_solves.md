# What it solves

Consider this instruction, where we have to add the two numbers 1 and 2.

## Assembly

```assembly
addi x5 x0 1
addi x6 x0 2
add x7 x5 x6
```

## Binary

```binary
000000000001001010000000000100110000000000100011000000000001001100000000011100101000001101100011
```

## Binary in human readable format

```binary
0000000 00001 00101 000 00000 0010011
0000000 00010 00110 000 00000 0010011
0000000 00111 00101 000 00110 1100011
```

## Binary with a mistake. Happy debugging

```binary
000000000001001010000000000100110000000000100011000000000001001100000000010100101000001101100011
```

The purpose of an assembly language can easily be seen with the help of the above example. Assembly language with the help of its syntax makes it easier to code and not worry about trivial tasks such as opcodes, address calculations, etc. Mistakes if any can easily identified in assembly
rather than in binary. Imagine finding such mistakes in a pool of 0's and 1's!
