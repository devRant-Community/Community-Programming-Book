# Introduction

## Inception

C++ is an immensely popular and a massive programming language which is built on the foundation of modern, object oriented, programming concepts. Originated in 1979, by *Bjarne Stroutrup*, he
started working on "C with classes", the predecessor of C++. The goal and motivation was to create a fast and powerful language, building its roots upon the performance, efficiency, and portability
of the widely used programming language - **C**. His original idea was to extend the C compiler with additional features such as *classes*, *strong typing*, *inlining*, and *default arguments*.

In 1983, the language was renamed to *C++*, with the ++ being the increment operator in C. This is when some more features were added to the language like *virtual functions*, *function name &
operator overloading*, *references*, *memory allocation using new/free*, and *two forward slash comments - //* to name a few. This was also time when the first standalone compiler for C++ was
created named *CFront*.

The book **The C++ Programming Language** was released in 1985 which became the language reference since there was no official standard at that time.

Since then, the language has been continuously evolving, most notably in C++11 standard, and has captured interests of many programmers throughout the world. Many educational institutes provide
fundamental courses on C and C++ with C++ as the epicenter for the concepts of *Object Oriented Programming*.

Currently, the latest standard of C++ which has been released is C++17, however most compilers have not implemented the standard as of *May 24, 2018*. C++14 has been implemented in the various
popular compilers like - *GNU Compiler Collection (gcc)*, and *clang*.

## What is C++?

A very comprehensive, vast, and powerful language is perhaps the most concise definition (and over simplification) of C++. Although considered a high level language, with the advent of languages
like *Python*, and *Ruby*, it is now considered low level along the lines of C, and rightfully so. The language contains many constructs (most prominently - pointers) which it borrows from C, a low
level programming language, and is highly used in areas like *Compiler Design*, *Video Game Development*, and *IoT*.
It is a fully compiled language, meaning, it compiles the code to native binary which can be directly executed on the system. However, since it is compiled to native code, the binary compiled on
one architecture and/or kernel **cannot** be used on different architecture/kernel without recompilation. Hence, if one compiles a C++ program on Linux, the same binary cannot be used on, say,
Mac OS.

The reason for its prominance in fields like IoT is that it has quite low memory footprint, that is, it used a very low amount of system memory to work, depending on the program or software written.
This is, again, due to the fact that the language compiles code to native binary and the generated binary does not rely on a virtual machine for code execution on the system.

Now, with all the power and amazing features of C++, one must still understand where the language is most suitable and where not, because, in the wrong situation, C++ can wreak havoc on one's system
or simply be too cumbersome to use. Let's take a glimpse into this.

## Why C++?

C++ is a high performance language, and when used correctly, can give performance seconded only by the likes of C and Assembly. Therefore, any application which requires high performance, like
even finance and stock based applications, highly benefit by utilizing C++ language to build the codebase with.

Being one of the most popular languages, it has a very large community backing which is quite helpful, especially, when one encounters some trouble or issue. Since there is great community support,
it also has a slew of various libraries which can be used to enhance the application or make it easier to develop. Be it graphics, audio, network, input, and even AI and Machine Learning, C++
contains libraries for all of them. One should also understand that C++ supports code which is written in C. Hence, any library or piece of code which is written in C, works with C++ directly
without any modification.
(Note: C++ supports C, but the internal architecture of both languages are quite different so do **not** consider C to be a part of C++ and the code design choices between C and C++ can also
differ significantly)

The language is highly sought after for game development as well. Video games require heavy performance to accomplish the exuberant amount of calculations and processing. C++ fits this scenario
perfectly. Hence, most games use C++ as the language of choice for development. There are many engines available for game development as well, most significantly, the *Unreal Engine*.

One may have heard of Google's *Tensor Flow* - the highly acclaimed and lauded Artificial Intelligence library. Although it is used from Python, the library itself is built primarily using C++.
That alone states how powerful this language can be in many areas.

But, there are cases when using C++ is simply not worth it. Let's take a look into that.

## Why Not C++?

Since C++ is a rather low level language (by today's standards), it requires a large amount of code to be written for performing tasks. Simply put, the codebase of C++ can get quite large, if not
extremely massive, if the application in question is large. This, in turn means that, to build an application which, perhaps, can be written in tens of lines of code in high level languages like
Python and Ruby, can take hundreds of lines of code in C++.

Therefore, a language like C++ is simply not usable for creating scripts which perform tasks that don't require heavy performance. Here, the compiled nature of C++ is also not useful because it is
quite cumbersome to keep compiling a small piece of code whenever a change is made.

For example, if we create a script to copy and/or move files around on our computer based on specific constraints, it can be rather easy to perform on a language like Python and Ruby, or even
*Bash*. But to build the same script on C++ would be counter-productive to say the least.

This holds especially true because scripts usually tend to be cross platform and we expect them to simply run on whichever system we need. But for C++, we will have to compile the code first which
would require us to have the compiler toolchain on the system itself.

Hence, using C++ in such cases is not useful.

## Conclusion

C++ is a great language, used in most enterprise level of industries and open source communities alike, to build high performance and low resource applications. The language is very flexible and
allows one to perform virtually any task one may want to. From building a web browser (Chromium), to building massive libraries (TensorFlow), C++ does a very good job as a tool to build them.

It is a very in-depth language and provides constructs and mechanisms for many concepts. One cannot learn the language by reading a book and it is a must to actually write programs and understand
errors as they arrive to be able to understand the language and become proficient in it. And, *always* have the mindset of learning new things about the language. There is always a very high chance
that C++ can surprise one with some nooks and crannies or features that it contains, so, it will take a long long time for someone to imbibe C++ into oneself. However, the journey is definitely
rewarding, and fun.

Finally, in no way, is C++, a *best* language to use for everything. No language is, but one should understand when to use which language so that development is easier and work gets done
efficiently.
Therefore, it is wise to work with other languages as well to improve understanding of programming in general and to be able to use the right tool at the right time.
