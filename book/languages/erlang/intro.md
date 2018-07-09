# Introduction

## Inception

**Erlang** first appeared in the Ericsson laboratory and it is successfully used in projects requiring **high scalability and resistance to failures**.

It is a **functional**, **dynamic language** with strict typing in which the main focus was on concurrency and **processing capabilities distributed**.

Erlang **was a proprietary programming language** used by **Ericsson**, but since **1998** when the source code was open sourced
and is gaining popularity day by day.

It is successfully used in **commercial products** (for example: **WhatsApp**) around the world that go many times beyond its **telecommunications roots**.

> The file extension for Erlang are **.erl** and **.hrl**

## Erlang features

* **Concurrency**

    Processes are the **basic elements** in the structure of applications written in Erlang.
    The implementation of concurrent processes is **independent** of the system and does not use mechanisms specific to the given environment like threads, for example.
    Creating and managing Erlang processes is very simple, while in other languages ​​concurrency provides many problems and is the source of a small number of different types of errors.
    Erlang processes are **much lighter** than system ones (about 300 bytes per one process), thanks to which the processes of creating and destroying processes are *relatively* cheap computationally and memory.
    In a single Erlang system **possible** is to create up to one million processes without significant performance degradation.
    **In Computer Language Shootout in the competition for sending messages between thousands of threads (thread-ring) solution written in Erlang ranks first in terms of performance and code volume**.
    Communication between processes in Erlang (due to the fact that the processes do not divide shared memory) takes place by sending asynchronous messages.
    A queue is associated with each process **FIFO**, used to receive messages.
    The receiving process determines whether process the message or not.
    Every process has its own mailbox, in the form of a queue in which they are stored messages sent by other processes until they are read.
    Receiving messages is done by the **pattern matching mechanism**.
    After reading the message, the Erlang process returns to **execution**.
    To create messages can be used **any data structure** (integers, floating point, characters, atoms) and even functions.

* **Dispersion**

    The dispersed mechanism is **built into** the language. You can create processes with any node on any node.
    The process *can* be created on remote node, and communication with it is transparent (communication with the remote process is carried out in **exactly the same way as with local process**).

* **Error handling**

    Error handling generally takes place through the **supervision of some processes over others**.
    When the process breaks down, it leaves and sends a message to the process a control who can take the appropriate action - e.g. restart or end broken process and start the next one.
    This approach to programming increases reliability and makes the code less complicated.
    In addition, the process, the control and supervised process do not have to be on the same physical machine, thanks to which it is relatively easy to program systems high availability, in which particular functions are performed by efficient nodes at a given moment.

* **Hot code replacement (Hot code upgrade)**

    *Many* systems **can not be stopped for software exchange purposes**.
**In Erlang you can exchange the code in the running system** (in the system co-exist for a moment both codes), and thus install bug fixesand upgrades without stopping the system.

* **Support for multiprocessor systems**

    From the **R11** version, Erlang's environment *can* automatically exploit the potential hidden in multi-core processors and systems multiprocessor.
    Previously, to use such a system belonged run several copies of the virtual machine, which unfortunately increased memory consumption, and increased the cost of sending messages unnecessarily between processes on one computer.
