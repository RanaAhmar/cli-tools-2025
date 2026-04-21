# CLI Tools 2025 🛠️✨

[![Sponsored by Stackaura](https://img.shields.io/badge/Sponsored_by-Stackaura-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.stackaura.com/)
[![CLI Tools](https://img.shields.io/badge/CLI_Tools-Curated-blue.svg?style=for-the-badge)](https://www.stackaura.com/)

A meticulously curated list of modern, blazing-fast, and rust-rewritten Command Line Interface (CLI) tools that every developer should know in 2025. Boost your terminal productivity with these modern alternatives to classic Unix commands.

---

<div align="center">
  <h3>Sponsored by <a href="https://www.stackaura.com/">Stackaura</a></h3>
  <p>Building the next generation of developer tools and workflow automation.</p>
  <a href="https://www.stackaura.com/"><img src="https://img.shields.io/badge/Visit_Stackaura-Black?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Visit Stackaura" /></a>
</div>

---

## 🌟 Why This List?

The terminal landscape has evolved dramatically. While the classic GNU/Unix tools are robust, modern tools (often written in Rust or Go) offer significantly better performance, smarter defaults, colorful outputs, and highly improved user experiences.

This repository compiles the definitive list of modern CLI tools you should be using in 2025.

## 🚀 The Tools

### Core Nav & File Interaction

| Classic | Modern Alternative | Why it's better? |
|---------|-------------------|------------------|
| `ls` | **[eza](https://github.com/eza-community/eza)** or **[lsd](https://github.com/lsd-rs/lsd)** | Git integration, icons, color-coded metadata. |
| `cd` | **[zoxide](https://github.com/ajeetdsouza/zoxide)** | Smarter, faster directory navigation based on muscle memory. |
| `cat` | **[bat](https://github.com/sharkdp/bat)** | Syntax highlighting, Git integration, automatic paging. |
| `find` | **[fd](https://github.com/sharkdp/fd)** | Much faster, colorized output, smart case sensitivity, ignores hidden/.git by default. |

### Search & Text Processing

| Classic | Modern Alternative | Why it's better? |
|---------|-------------------|------------------|
| `grep` | **[rg (ripgrep)](https://github.com/BurntSushi/ripgrep)** | Unprecedented speed, respects `.gitignore`, better defaults. |
| `sed` / `awk` | **[sd](https://github.com/chmln/sd)** or **[sad](https://github.com/ms-jpq/sad)** | Intuitive find & replace without the arcane regex syntax. |
| *JSON parsing*| **[jq](https://github.com/jqlang/jq)** / **[jaq](https://github.com/01mf02/jaq)** | Indispensable for manipulating JSON data in the shell. |

### System & Task Management

| Classic | Modern Alternative | Why it's better? |
|---------|-------------------|------------------|
| `top` | **[btm (bottom)](https://github.com/ClementTsang/bottom)** or **[htop](https://htop.dev/)** | Beautiful UI, customizable widgets, better process filtering. |
| `du` | **[ncdu](https://dev.yorhel.nl/ncdu)** or **[dust](https://github.com/bootandy/dust)** | Interactive terminal UI for analyzing disk space. |
| `diff` | **[delta](https://github.com/dandavison/delta)** | Syntax-highlighted, side-by-side git diffs. |

### Networking & Web

| Classic | Modern Alternative | Why it's better? |
|---------|-------------------|------------------|
| `curl` | **[httpie](https://github.com/httpie/cli)** | Human-friendly HTTP client, colorized JSON responses. |
| `ping` | **[gping](https://github.com/orf/gping)** | Ping, but with a real-time graph. |
| `dig` | **[dog](https://github.com/ogham/dog)** | Colorful and modern DNS client. |

## 📦 How to Install

Most of these tools can be installed via your system's package manager:

**macOS (Homebrew):**
```bash
brew install eza zoxide bat fd ripgrep bottom dust git-delta httpie
```

**Ubuntu/Debian (using cargo where unvailable):**
```bash
sudo apt install bat fd-find ripgrep httpie
# Install remaining via Cargo
cargo install eza zoxide bottom du-dust git-delta
```

## 🤝 Contributing

Have a modern CLI tool that changed your life? We welcome contributions!
1. Fork the repository
2. Add your tool to the relevant category
3. Briefly explain why it's a worthy alternative
4. Open a pull request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Built with ❤️ for modern terminal wizards by [Stackaura](https://www.stackaura.com/).*
