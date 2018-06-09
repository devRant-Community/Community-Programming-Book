# Introduction

## Inception

C# was Developed by Anders Hejlsberg at Microsoft as part of .NET framework initiative in the late 2000's.

The name comes from a musical notation where a sharp symbol sets the note higher in pitch by one semitone, which is similar to the story of the C++ name, where ++ being the increment operator. 
some say that the sharp symbol also resembles a four "+" symbols (in a 2x2 grid), implying that the language is an increment of C++.

In its early 1.0 version, C# looked a lot like it's predecessor Java (released in 1991). 
But it has grown quickly since it was first created, with extensive support from Microsoft promoting C# as it's primary .NET framework language it gained a large audience and became one of the most popular programming languages in the world.

By the time this chapter was written, C# version stands at 7.0 and is continuously evolving.

## What is C#?

C# is an elegant object-oriented language that enables developers to build a variety of powerful and secure applications.

It can be used to create Windows apps, Web services, Mobile apps, VR, Games and much more.

C# is a managed code, meaning that C# program requires and only executes under the management of a CLR (Common Language Runtime) virtual machine.

Same as Java running on JVM (Java Virtual Machine), C# runs on .NET Framework.

## Why C#?

C# was designed to be simple and easy to use, it's syntax is very natural and non-verbose. As a high-level language, it abstracts away most of the complex details, giving the user an ability to focus on its pure programming tasks instead of worrying about the little bits.

While abstracting away the details, C# doesn't limit your abilities and gives you the option to work on a lower level using features like Interoperability which enables you to take advantage of unmanaged code such as C/C++ directly from your code. 

C# is a managed programming language. Being one, allows you to not worry about freeing up the memory. The memory cleanup is dealt by the GC (Garbage collector) of the .NET Framework. 

Another advantage of managed code is that it becomes platform-independent, meaning that it can be run on any platform with .Net Framework installed, but it's not limited to it. Thanks to Mono project, there are other technologies that support C# as it's primary language. Tools like Unity and Xamarin allow you to write C# code and run it on any platform of your choice.

It's a type-safe compiled language, meaning that your code is verified by the compiler before it's execution, making your code more resilient to runtime errors by catching them ahead of time.

C# is part of C-family programming languages, anyone familiar with any of the C-family languages such as C, C++ or Java will feel comfortable using it.

## Why not C#?

Compiled code is usually seen as an advantage, but it also has it's own drawbacks. If you change any part of your code, you must recompile the whole application, this makes the deployment process a bit tedious.

Even though C# is a compiled language, it's not as fast as native code compiled languages. The two main reason for that is that C# being compiled to IL (intermediate language) instead of machine code and the overhead added by the GC (garbage collector)

Finally, even though C# is a Cross-Platform, it is still used mainly within .Net ecosystem and you most likely to see C# on Windows based OS, but it's gaining popularity (especially since .NET Core release) in latest years and can be seen on other platforms such as Mac and Linux.

## Conclusion

C# is a great modern language, with a large development community and Microsoft support.
It's used in many enterprise applications on client and server sides.

In the next chapters, we'll dive into C# and explore it from the ground up.
