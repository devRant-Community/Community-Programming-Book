# Disadvantages

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
