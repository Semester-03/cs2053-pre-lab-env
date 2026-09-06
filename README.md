# Pre-Lab – Environment Setup & Submission Standards

CS2053 – Computer Architecture  
Department of Computer Science and Engineering, University of Moratuwa

## Overview

- RISC-V toolchain configuration (riscv-none-elf-gcc / riscv64-unknown-elf-gcc)
- Ripes visual computer architecture simulator setup and verification
- Repository directory structures and submission packaging standards
- Git workflow, Conventional Commits, and automated grading boundaries

## Theory Alignment

- Canonical lecture concepts, ISA specifications, and architecture theory are documented in the [CS2053-Weekly-Notes](https://github.com/CS2053-Computer-Architecture/CS2053-Weekly-Notes) repository.

## Repository Structure

```text
.
├── setup/
├── docs/
├── evidence/
└── README.md
```

## Engineering & Git Standards

- **Commit Conventions**: All commits follow the Conventional Commits format (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`).
- **Branching Workflow**: Assembly programs, processor simulations, and analysis tasks utilize feature branches prior to merging into `main`.
- **Reproducibility**: Register trace tables, Ripes simulation screenshots, and benchmark logs are preserved in `evidence/`.

## Academic Context

Department of Computer Science and Engineering, University of Moratuwa.
