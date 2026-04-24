<p align="center">
  <img src="assets/images/banner.png" width="800" alt="XCX Banner">
</p>

# xcx-lang

XCX is a statically typed, multi-paradigm backend language built in Rust. HTTP, SQLite, JSON, crypto, and file I/O are part of the language itself - no frameworks, no ORMs, no boilerplate. Write logic; the runtime handles the rest.

## Core repositories

| Repo | Description |
|------|-------------|
| [xcx](https://github.com/xcxlang-org/xcx) | Compiler, bytecode VM, tracing JIT (Cranelift), and CLI |
| [pax](https://github.com/xcxlang-org/pax) | PAX package manager |
| [xcx-vscode](https://github.com/xcxlang-org/xcx-vscode) | vscode-extension |
| [mathlib](https://github.com/xcxlang-org/math-lib) | Standard library and math extensions |


## Quick start

**1. Install** - download `xcx-setup.exe` from [xcxlang.com](https://xcxlang.com) or from the [Releases tab](https://github.com/xcxlang-org/xcx/releases), run the installer, and follow the on-screen instructions. `xcx` will be added to your PATH automatically.

**2. Hello World** - create a file and run it:

```xcx
>! "Hello, World!";
```

```bash
xcx hello.xcx
```

**VS Code extension** - syntax highlighting and snippets available at [xcxlang-org/xcx-vscode](https://github.com/xcxlang-org/xcx-vscode).


## Ecosystem

| Resource | Link |
|----------|-------|
| Official site | [xcxlang.com](https://xcxlang.com) |
| Documentation | [xcxlang.com/docs/index.html](https://xcxlang.com/docs/index.html) · [/docs in repo](https://github.com/xcxlang-org/xcx/tree/main/docs) |
| PAX Registry | [pax.xcxlang.com](https://pax.xcxlang.com) |


## Status

| Version | Status | Notes |
|---------|--------|-------|
| **XCX 3.0** | ✅ Current | *The Database & Ecosystem Update* - native SQL, PAX Registry Preview, strict type system |
| **XCX 4.0** | 🔧 Planned | Full architectural rewrite - decoupled from Windows API, further JIT/VM optimizations, possible Linux support |

XCX is developed by a single contributor. The language is usable for small backend services and tools; production use in large systems is not recommended at this stage.
