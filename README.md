# Nano-P4 Specification

A mechanized formal specification of **Nano-P4**, an educational dialect of P4,
written in [P4-SpecTec](https://github.com/kaist-plrg/p4-spectec).

The specification covers:

- **Syntax and IR**: surface syntax and intermediate representation of Nano-P4.
- **Static semantics**: type system / well-formedness rules (`5.*-typing-*`).
- **Loading**: elaboration of a program into a runtime context (`7.*-load-*`).
- **Dynamic semantics**: evaluation relations (`8.*-eval-*`).
- **Nano-switch**: top-level packet-processing pipeline that ties parsing,
  filtering, and forwarding together (`9-nano-switch.watsup`).

This repository is the finished **artifact** of the tutorial
[*Mechanizing the Nano-P4 Specification with P4-SpecTec*](https://github.com/pacokwon/nano-p4-tutorial).
Read the tutorial to see the guided, prose explanation of *why* each rule looks
the way it does.

## License

Licensed under the Apache License, Version 2.0.
