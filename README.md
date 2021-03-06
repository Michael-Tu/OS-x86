# OS-x86

A simple functional Operating System implemented on top of the Pintos framework for x86 instruction set.

This project is done in a group effort for UC Berkeley CS162: Operating System class. 

The team consists of Andrew Halle, Chris Hinrichs, Michael Luo, and myself.

## Specs & Design Documents

* **Part 1: Threads**: [spec](specs/proj1.pdf), [design doc](design-doc/threads.md)
* **Part 2: User Programs**: [spec](specs/proj2.pdf), [design doc](design-doc/user-programs.md)
* **Part 3: File Systems**: [spec](specs/proj3.pdf), [design doc](design-doc/file-systems.md)

*Note*: due to correctness considerations, the working part 1 `threads` implementation is under the `threads` branch, while the part 2 & 3 user program and file system implementation is under the `master` branch.

##  Additional Features

In addition to the OS, I also implemented the following programs:

* A working basic shell terminal
* A HTTP Server
* Memory allocation `malloc`

## Dependencies
You will need a machine that supports x86 instruction set. The easiest way to do it is through a Virtual Machine (VM). You can download one such Vagrant VM from [UC Berkeley's CS162 Repo](https://github.com/Berkeley-CS162/vagrant/).
