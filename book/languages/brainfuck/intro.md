
# Introduction

Brainfuck is the most famous esoteric programming language ever made. It's an esoteric language, so it was not meant to be used
in solving real world problems (but, no one forbids You to!). The language can't be classified clearly. Partly it's a very high
level language - Brainfuck doesn't bind itself to any architecture making it very portable language. On the other hand, it's very
low level language - it supports only addition and subtraction, basic control structure (`while`-like loop), basic I/O (terminal
only, shrinking capabilities to the absolute minimum), and indefinitly long tape where any byte can be stored arbitrarily. Brainfuck
is Turing complete, meaning that it is in the same computational class as universal Turing machines. This, plus it's amount of
instructions, makes it a most popular example of a Turing tarpit. This can be proven in many ways, with various restrictions on
the brainfuck program or interpreter.

Daniel Cristofani wrote universal Turing machine emulator in Brainfuck which is so small we can quote it here:

```bf
+++>++>>>+[>>,[>+++++<[[->]<<]<[>]>]>-[<<+++++>>-[<<---->>-[->]<]]<[<-<[<]+<+[>]<<+>->>>]<]<[<
]>[-[>++++++<-]>[<+>-]+<<<+++>+>[-[<<+>->-[<<[-]>>-[<<++>+>-[<<-->->>+++<-[<<+>+>>--<-[<<->->-
[<<++++>+>>+<-[>-<-[<<->->-[<<->>-[<<+++>>>-<-[<<---->>>++<-[<<++>>>+<-[>[-]<-[<<->>>+++<-[<<-
>>>--<-[<<++++>+>>+<-[<<[-]>->>++<-[<<+++++>+>>--<-[<->>++<[<<->>-]]]]]]]]]]]]]]]]]]]]]]<[->>[
<<+>>-]<<<[>>>+<<<-]<[>>>+<<<-]]>>]>[-[---[-<]]>]>[+++[<+++++>--]>]+<++[[>+++++<-]<]>>[-.>]
```

Simulation is one way to prove Turing completness:

 > If an interpreter for A can be implemented in B, then B can solve at least as many problems as A can.

There are some difficulties with this way of proving turing completness (ℒ), but for Brainfuck it's entirely sufficent. By theory,
Brainfuck is ℒ-complete too, so the proof is fully valid.

Brainfuck is amazing language. One must still understand where Brainfuck would be suitable, and where it doesn't particularly excel
at.
