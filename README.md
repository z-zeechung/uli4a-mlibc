**🏗️Development in progress. Commit welcomed.**

### <ruby>ULI4A<rt>/ˈju:lɪfɑ:/</rt></ruby> = Unix-like Interface for Any Platform

### mlibc = Minimal libc

🎯Target: Create a Unix-compatible layer for any platform. A platform could be an operating system, a bare machine, or something else.

🛣️Approach:

+ 📚A C library

+ 💻A graphic library

+ 📟A shell emulator

+ 📦A wrapper for any C compiler to emulate the behavior of GCC toolchain

📚mlibc: An easy-to-compile C library with minimal system interfaces, providing stability and good compatibility with current POSIX softwares.

📜Principles:

+ Strive to define as few system interfaces as possible

+ Unless necessary or specified in the C standard, avoid the use of marcos

+ Do not use conditional compilation

+ Keep things simple
