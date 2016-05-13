![](https://raw.githubusercontent.com/Mikescher/BefunUtils/master/README-FILES/icon_BefunWrite.png) BefunWrite
==========

BefunWrite is an IDE in which you can write a program in *TextFunge*, and compile it to valid Befunge-98 code.

> **NOTE:**  
>  
> While the generated Code practically is Befunge-98, you can use it in nearly every Befunge-93 interpreter.  
> Because it doesn't use a single command, which was not defined in Befunge-93, the only non-Befunge-93 feature is the extended file size.  
> Because this tool can generate fairly big Befunge-93 code, it often exceeds the size of 80x25, and is so no longer totally valid Befunge-93 code.
> But for the sake of confusion I will refer in the rest of these documents to it as Befunge-93 code.

![](https://raw.githubusercontent.com/Mikescher/BefunUtils/master/README-FILES/BefunWrite_Main.png)

In BefunWrite you write your source code in the, specially for this developed, language **TextFunge**.
BefunWrite supports you in this process with a lot of the basic IDE features you already know from other IDE's.  
After written you can compile your TextFunge code into BEfunge-93 code and execute it in **BefunExec**.

The main advantage for you is how you can easily generate even complex programs in Befunge.
Because TextFunge supports all the basic features of a procedural language you can use constructs like:

- if-clauses and switch-cases
- for-loops, while-loops, repeat-until-loops
- methods
- recursion
- global and local variables with different data-types
- GOTO's
- arithmetical and logical expressions

BefunWrite also provides an easy interface for the multiple compiler-settings, for more information please visit the individual manuals.


Download
========

You can download the binaries from my website [www.mikescher.com](http://www.mikescher.com/programs/view/BefunUtils)

Set Up
======

*This program was developed under Windows with Visual Studio.*

You need the other [BefunUtils](https://github.com/Mikescher/BefunUtils) projects to run this (Especially BefunExec and BefunGen).  
Follow the setup instructions from BefunUtils: [README](https://github.com/Mikescher/BefunUtils/blob/master/README.md)