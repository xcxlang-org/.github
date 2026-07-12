<p align="center">
  <img src="https://github.com/xcxlang-org/xcx-branding/blob/main/banner/svg/banner.svg" width="800" alt="XCX Banner">
</p>

# xcx-lang

XCX is a statically typed, multi-paradigm backend language built in Rust. HTTP, SQLite, JSON, crypto, and file I/O are part of the language itself - no frameworks, no ORMs, no boilerplate. Write logic; the runtime handles the rest.

## Core repositories

| Repo | Description |
|------|-------------|
| [xcx](https://github.com/xcxlang-org/xcx) | Compiler, bytecode VM, tracing JIT, and CLI |
| [pax](https://github.com/xcxlang-org/pax) | PAX package manager |
| [xcx-web-playground](https://github.com/xcxlang-org/xcx-web-playground) | Browser-based playground — no installation required |
| [xcx-vscode](https://github.com/xcxlang-org/xcx-vscode) | vscode-extension |
| [mathlib](https://github.com/xcxlang-org/math-lib) | Standard math library extensions |

## Quick start

**1. Install**

- Windows: download `xcx-setup.exe` from [xcxlang.com](https://xcxlang.com) or the [Releases tab](https://github.com/xcxlang-org/xcx/releases)
- Linux: `curl -sL https://xcxlang.com/install.sh | bash`, or grab the tarball from Releases
- FreeBSD (experimental, no guarantees): [xcx-experimental-builds](https://github.com/xcxlang-org/xcx-experimental-builds)

`xcx` will be added to your PATH automatically.

**2. Hello World**

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
| Playground | [playground.xcxlang.com](https://playground.xcxlang.com) |

## Status

| Version | Status | Notes |
|---------|--------|-------|
| **XCX 4.0** | ✅ Released | Full architectural rewrite of the VM and JIT, zero-copy JSON, arena allocator, reworked REPL |
| **XCX 4.1** | ✅ Released | Reduced cross-function call overhead, inlined collection size reads, pointer analysis optimizations, `array.slice()`, `json.keys()` |
| **XCX 4.2** | 🔧 In development | Compiler pipeline improvements and further performance work |

XCX runs on Windows, Linux (Ubuntu, Arch/Manjaro, and generally all major distros), and has an experimental FreeBSD build.

XCX is developed by a single contributor. The language is usable for small backend services and tools; production use in large systems is not recommended at this stage.
