# Disadvantages

C has no support for closures, no guaranteed support of tail calls

There is no way to portably inspect the call stack. Hence, you cannot code something like GNU backtrace or `longjmp`/`setjmp` in
portable C. Also, coding precise garbage collectors is very painful.

There is no ABI, every vendor made up their own. Higher level constructs have to be manually created or third-party libraries and
other solutions used.

There are no namespaces, so it's easy to pollute global namespace and wreck something up.

Finally, C doesn't support exceptions and object oriented programming.
