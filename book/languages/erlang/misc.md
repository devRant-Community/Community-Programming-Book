# Some interesting facts about Erlang


* WhatsApp messaging system is build on Erlang, it supports over 800 million users and 30 billion messages per day

* bet365 uses Erlangin their Online Gambling & Betting industry.

* Erlang transports 40% of all telecoms data

* Erlang can be used in everywhere on the backend

* 3 of the leading banks are build on Erlang

* 2 of the leading blockchains are build on Erlang

## Example of **Hello World** code written in Erlang compared to other languages

### **Erlang**

```Erlang
-module(hello).
-export([hello_world/0]).
hello_world() -> io:fwrite("hello, world\n").
```

After this is done, you'll need more work.
Save it as hello.erl and compile it from the erlang shell.
Don't forget the full-stop ("period" in American English) at the end of each command, as shown:

        Erlang (BEAM) emulator version 4.9.1 [source]
        Eshell V4.9.1  (abort with ^G)
        c(hello).
        {ok,hello}

(on unix systems you start the erlang shell by typing "erl" at the command line.
On Windows, open a command prompt window and type "werl", or find the Erlang icon in the programs menu).
To run the program from the Erlang shell:

        hello:hello_world().
        hello, world
        ok


### **JavaScript**

```JavaScript
"use strict"  // This declares strict mode and using it is a good security practice.
console.log("Hello world!");  // semicolon is not mandatory but recommended
```

### **Kotlin**

```Kotlin
fun main(args: Array<String>) {
    println("Hello world!")
}
```

### **Python**

```Python
print "Hello world!"
```

### **Ruby**

```Ruby
puts "Hello world!"
```