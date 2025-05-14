# Noxia Syntax Highlighting for VS Code

This extension adds syntax highlighting and editor support for the [Noxia](https://github.com/yourname/noxia) systems programming language.

> Noxia is a clean, powerful, RISC-inspired systems language designed from scratch — this extension gives you basic syntax support inside Visual Studio Code or VSCodium.

---

## ✨ Features

- Syntax highlighting for:
  - Keywords (`fn`, `let`, `const`, etc.)
  - Types (`int`, `ptr`, `u8`, etc.)
  - Comments (`//`)
  - Strings and numbers
- File association for `.nx` files
- Lightweight and fast — zero runtime JS

---

## 📦 Install

### Local (Recommended for Devs)

1. Clone this repo or download it.
2. Inside the folder, run:

   ```bash
   npm install -g @vscode/vsce  # if not already installed
   vsce package
   codium --install-extension noxia-syntax-highlighting-0.0.1.vsix

