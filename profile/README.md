<p align="center">
  <img src="../assets/img/banner.png" width="800" alt="XCX Banner">
</p>

# xcx-lang

XCX is a statically typed, multi-paradigm backend language built in Rust. HTTP, SQLite, JSON, crypto, and file I/O are part of the language itself - no frameworks, no ORMs, no boilerplate. Write logic; the runtime handles the rest.

## Core repositories

| Repo | Description |
|------|-------------|
| [xcx-compiler](https://github.com/xcx-lang/xcx-compiler) | Compiler, bytecode VM, tracing JIT (Cranelift), and CLI |
| [pax](https://github.com/xcx-lang/pax) | PAX package manager |
| [xcx-site](https://github.com/xcx-lang/xcx-site) | Official website source |
| [xcx-stdlib / mathlib](https://github.com/xcx-lang/xcx-stdlib) | Standard library and math extensions |


## Quick start

**1. Install** - download `xcx-setup.exe` from [xcxlang.com](https://xcxlang.com) or from the [Releases tab](https://github.com/xcx-lang/xcx-compiler/releases), run the installer, and follow the on-screen instructions. `xcx` will be added to your PATH automatically.

**2. Hello World** - create a file and run it:

```xcx
>! "Hello, World!";
```

```bash
xcx hello.xcx
```

**VS Code extension** - syntax highlighting and snippets available at [xcx-lang/xcx-vscode](https://github.com/xcx-lang/xcx-vscode).


## Ecosystem

| Resource | Link |
|----------|-------|
| Official site | [xcxlang.com](https://xcxlang.com) |
| Documentation | [xcxlang.com/docs/index.html](https://xcxlang.com/docs/index.html) · [/documentation in repo](https://github.com/xcx-lang/xcx-compiler/tree/main/documentation) |
| PAX Registry | [pax.xcxlang.com](https://pax.xcxlang.com) |


## Status

| Version | Status | Notes |
|---------|--------|-------|
| **XCX 3.0** | ✅ Current | *The Database & Ecosystem Update* - native SQL, PAX Registry Preview, strict type system |
| **XCX 4.0** | 🔧 Planned | Full architectural rewrite - decoupled from Windows API, further JIT/VM optimizations, possible Linux support |

XCX is developed by a single contributor. The language is usable for small backend services and tools; production use in large systems is not recommended at this stage.