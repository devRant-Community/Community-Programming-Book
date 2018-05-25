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
