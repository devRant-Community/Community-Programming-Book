# Where would you use assembly?

In recent times programming in assembly is rare because automated programs exist(assemblers)
 which convert higher level languages into assembly and subsequently into machine language.
 Since there exists a strong correspondence between machine code and assembly mnemonics it can be
used in applications where speed and performance is of importance but the application itself occupies minimal space.

> Computers powering earlier Apollo missions were programmed in
 assembly but the entire code was if written in a book would be about 5 feet in height.

Some places where direct programming assembly language can be used:

* To build software which requires  serious machine level optimizations or to beat compilers in code optimization.
For eg: some system software in an OS (not needed though as modern compilers do a pretty good job).

* In embedded programming where space is limited to an extent that higher level languages
  (like C) and an assembler/compiler cannot included in storage.

* To access hardware specific features  which are either platform specific or too uncommon and not
  available for optimization in higher languages such as C.

* Written for custom hardware that don't have a mechanism to convert high level code
  into binary. The Appollo-11 Lunar mission is a good example as it was powered by programs
  written in assembly in  an era where high level languages did not exist.
