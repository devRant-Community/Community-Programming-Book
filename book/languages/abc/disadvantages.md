# Disadvantages

* Some issues with syntax like uppercase for keywords.

* Variables are persistent and global. Memory management thus is an issue.

* It has a very monolithic design that is low-level optimizations to the code is not possible.

* I/O from files was not implemented. Thus, it could not be used for reading and writing from files.

* Because of the way variables were implemented it was not possible to implement temporary or
  session specific variables without exclusively deleting them.
