XCX is a statically typed, multi-paradigm backend language built in Rust. HTTP, SQLite, JSON, crypto, and file I/O are part of the language itself - no frameworks, no ORMs, no boilerplate. Write logic; the runtime handles the rest.

## Core repositories

| Repo | Description |
|------|-------------|
| [xcx](https://github.com/xcxlang-org/xcx) | Compiler, bytecode VM, tracing JIT, and CLI |
| [pax](https://github.com/xcxlang-org/pax) | PAX package manager |
| [xcx-web-playground](https://github.com/xcxlang-org/xcx-web-playground) | Browser-based playground — no installation required |
| [xcx-vscode](https://github.com/xcxlang-org/xcx-vscode) | vscode-extension |
| [mathlib](https://github.com/xcxlang-org/math-lib) | Standard math library extensions |
| [xcx-benchmarks](https://github.com/xcxlang-org/xcx-benchmarks) | Benchmark suite and methodology |

## Ecosystem

| Resource | Link |
|----------|-------|
| Official site | [xcxlang.com](https://xcxlang.com) |
| Documentation | [xcxlang.com/docs/index.html](https://xcxlang.com/docs/index.html) · [/docs in repo](https://github.com/xcxlang-org/xcx/tree/main/docs) |
| PAX Registry | [pax.xcxlang.com](https://pax.xcxlang.com) |
| Playground | [playground.xcxlang.com](https://playground.xcxlang.com) |

XCX runs on Windows, macOS, and Linux (Ubuntu, Arch/Manjaro, and generally all major distros), with an experimental FreeBSD build.

XCX is developed by a single contributor and is currently in a runtime stabilization phase. Not recommended for production use yet, but experimentation, small backend services, and tools are very much encouraged.
