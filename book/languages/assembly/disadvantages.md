# Shortcomings

Consider the same example as in the previous section to add two numbers, lets say 1 and 2, but this time it is written in C.

```C
#include<stdio.h>
int main()
{
    int x = 1;
    int y = 2;
    int z = x+y;
    return 0;
}
```

As the reader might have observed coding in C turns out to be much more easy than assembly, because it's less verbose and each line of code is more intuitive compared to either assembly or binary.

But there is a trade-off between the performance offered by assembly language and C.

* Coding in assembly sometimes is not intuitive and requires a lot of time to understand the code compared to higher level languages such as C, which is less verbose and is more descriptive.

* The entire code in assembly language could turn out to be monstrous in some stage cannot, because of which it cant't be handled or maintained easily.

* Manually writing in assembly language for large programs such as an OS for instance can be frustrating.

## Birth of the higher-level languages

Even though assembly language offers high performance it cannot be effectively used to build user applications, because a higher abstraction is necessary to do so.
Also it is not "programmer friendly" in the sense that it still remains a low level language and can be difficult to grasp or understand.
Hence a need for abstracting assembly language itself arises which is both understandable and "programmer friendly".

From this need new assembly languages were born with a higher abstraction, which were more "programmer friendly" than the initial low level assembly languages but they still remained assembly languages.

Afterwards even higher level languages were introduced which acted like an abstraction of assembly language itself. One of the most notable languages among these is C.
