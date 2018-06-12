# Where would you use assembly ?

Currently assembly is used very rarely, because nowadays we use higher-level languages which are "translated" through an assembler to assembly and then assembly makes machine code out of it.
Since machine code and assembly are tied together, assembly can be used in applications where speed and performance is of importance, to optimize directly the machine code.

> The Computers on-board of the spacecraft of the Apollo missions used assembly, if the entire code would be printed out it would occupy about 5 feet in height.

The assembly language can be used in these types of application:

* To build software which requires serious machine level optimizations or to beat compilers in code optimization. \
  For e.g.: System software in an OS (not needed though as modern compilers do a pretty good job).

* In embedded programming where space is limited to an extent that higher level languages
  (like C) can use more space than required or actually present.

* To access hardware features which are either platform specific or too uncommon and not
  available for optimization in higher languages such as C.

* Written for custom hardware that doesn't have a mechanism to convert high level code
  into binary. The Apollo 11 lunar mission is an example of this as it used code
  written in assembly in an era where high level languages did not exist.
