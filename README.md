# Hi, I'm Coxless

Developer based in Tokyo, Japan. I mostly write **Rust**, **TypeScript** and **Python**, and I like building small, sharp tools: command-line utilities, numerical code, and things that run AI models locally instead of in someone else's cloud.

Several of my projects are named after rowing — a *coxless* boat has no coxswain, a *thole* is the pin an oar pivots on, and a *hull* is what keeps it all afloat.

## What I'm working on

- **[thole](https://github.com/Coxless/thole)** — Scientific computing crates in pure Rust, with no BLAS or LAPACK underneath. Every algorithm is written from scratch, callable from Python, and has its mathematical properties proved in Lean 4. Early development.
- **[hull](https://github.com/Coxless/hull)** — A chat-history-style terminal: each command and its output is a block, and past sessions can be listed and resumed. Design stage.
- **[local-decision-model](https://github.com/Coxless/local-decision-model)** — A small encoder model that answers named questions about free text with typed, calibrated probabilities, exported to OpenVINO to run on an Intel NPU.

## Projects

### Command-line tools

| Project | What it does | Language |
|---|---|---|
| [execenv](https://github.com/Coxless/execenv) | Decrypts a SOPS-encrypted config in memory and hands off to your command via `execve`, so secrets never touch disk | Rust |
| [tiny-ai-shell](https://github.com/Coxless/tiny-ai-shell) | `ta "..."` turns natural language into a shell command using a local LLM (Ollama) | Rust |
| [vsgrep](https://github.com/Coxless/vsgrep) | A ripgrep-like local semantic (vector) search CLI. Work in progress | Rust |
| [github-notifier-ws](https://github.com/Coxless/github-notifier-ws) | Windows tray utility that filters GitHub notifications with YAML rules and shows only the ones that matter as toasts | Rust |

### Science and numerics

| Project | What it does | Language |
|---|---|---|
| [thole](https://github.com/Coxless/thole) | Pure-Rust scientific computing with Python bindings and Lean 4 proofs | Rust, Lean, Python |
| [fits-viewer](https://github.com/Coxless/fits-viewer) | Fast, lightweight FITS file viewer with GPU rendering, built for GB-to-TB astronomy data | Rust |
| [lbm-analysis](https://github.com/Coxless/lbm-analysis) | Lattice Boltzmann solver for 2D axisymmetric A–V electromagnetic problems, validated against exact Bessel-function solutions | Python, Jupyter |

### AI and agents

| Project | What it does | Language |
|---|---|---|
| [agent-auth-demo](https://github.com/Coxless/agent-auth-demo) | Hands-on demo of an in-browser LLM agent (WebLLM) calling an MCP server protected by OAuth 2.1 / PKCE, with Cedar policies for authorization | TypeScript |
| [local-decision-model](https://github.com/Coxless/local-decision-model) | Typed, calibrated answers from a small model running on an NPU | Python |
| [cc-terminal-mod](https://github.com/Coxless/cc-terminal-mod) | A Claude Code mod that opens a terminal pane in place and passes only the text you select to Claude | TypeScript |

### Web and JavaScript tooling

| Project | What it does | Language |
|---|---|---|
| [vite-plugin-wasm-hmr](https://github.com/Coxless/vite-plugin-wasm-hmr) | Vite plugin that watches Rust sources, rebuilds with wasm-pack, and triggers HMR inside the dev server | TypeScript |
| [textil](https://github.com/Coxless/textil) | ASCII art creation and editing studio: web app, npm package and CLI | TypeScript |
| [compatkit](https://github.com/Coxless/compatkit) | CLI for testing an npm package against a matrix of Next.js / React versions in a throwaway environment. Work in progress | TypeScript |

### Development environment

| Project | What it does |
|---|---|
| [setup-mise](https://github.com/Coxless/setup-mise) | Composite GitHub Action that sets up [mise](https://mise.jdx.dev/) on Ubuntu runners |
| [home-manager](https://github.com/Coxless/home-manager) | My Nix Home Manager configuration |
| [atcoder-starterkit-rust](https://github.com/Coxless/atcoder-starterkit-rust) | Starter kit for solving AtCoder problems in Rust |

## Tools I reach for

**Languages:** Rust · TypeScript · Python · Lean 4 · Nix · Shell

**Around them:** Next.js · Vite · WebAssembly · PyO3 · OpenVINO · Ollama · mise · Podman · GitHub Actions

## Writing

I write technical articles in Japanese on Zenn. The sources live in [Coxless/zenn](https://github.com/Coxless/zenn).
