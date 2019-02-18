# What it solves

Consider this instruction, where we have to add the two numbers 1 and 2.

## Assembly

```assembly
mov edx, 1
mov eax, 2
add eax, edx
```

## Hexadecimal

```hex
ba01000000b80200000001d0
```

## More readable hexadecimal

```binary
0:  ba 01 00 00 00   mov edx,0x1
5:  b8 02 00 00 00   mov eax,0x2
a:  01 d0            add eax,edx
```

## Binary code with a mistake. Happy debugging!

```binary
000000000001001010000000000100110000000000100011000000000001001100000000010100101000001101100011
```

The purpose of an assembly language can easily be seen with the help of the above example. Assembly language with the help of its syntax makes it easier to code and not worry about trivial tasks such as opcodes, address calculations, etc. Mistakes if any can easily identified in assembly
rather than in binary. Imagine finding such mistakes in a pool of just a numbers!
