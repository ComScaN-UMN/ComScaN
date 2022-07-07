# Software

[Home](README.md) | [Participants](participants.md) | [Papers](papers.md) | [Software](software.md)

------

All relevant software use in and developed by project participants
will be listed here.

The initial list of software follows:

- NF Lambda

- [ableC](https://melt.cs.umn.edu/ableC/) is an extensible
  specification of C (C11 standard) using
  [Silver](https://melt.cs.umn.edu/silver/). Users may direct the
  supporting tools to construct new extended versions of C from a set
  of independently designed language extensions. The composition is
  automatic and guaranteed to succeed. Several extensions have been
  developed; these include
  - Algebraic data types, with pattern matching
  - SQLite, with type-checked queries
  - Cilk, for task-based parallel programming
  - Regular expressions, with matching
  - An extension that combines these two to allow regular expressions to be used as patterns when matching on strings as part of an algebraic data type
  - Matrix features from MATLAB and a matlab function construct that generates the boilerplate FFI types and code for calling such functions from MATLAB
  - Term rewriting, inspired by the TOM system and Kiama
  - Closures / lambda-expressions
  - A partial implementation of HALIDE, a DSL for high performance matrix processing
 
  [ableC GitHub repository](https://github.com/melt-umn/ableC)
