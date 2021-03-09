# ZCom
A compiler for a Pascal-like language based on P6.

THIS IS A PLACEHOLDER REPO (I'll probably move this info to a better-named repository before uploading).

## History & Objectives

Pascal is a low-level programming language designed by Niklaus Wirth with a long history.

P6 is a simple Pascal compiler which generates a portable instruction format, and can be thought of as a good "reference implementation" for Pascal. A reference implementation of the instruction interpreter is also provided.

P6 in turn is based on P5 (and P4).

P6 supports the ISO 7185 Pascal standard ("at level 1"), and is able to compile itself (it's "self-hosting"). This has some benefits: the compiler can also be compiled on other standard Pascal systems, and we can use "compiling the compiler" as a way to test many features of the compiler.

ZCom is a fork of P6 (started in early 2021) aimed at incorporating more modern features (ideally without comprimising the existing ones).

Planned features include:

* Modularity (multi-file compilation, ideally with sane namespaces)
* Native compilation backends
* Additional/improved virtual backend
