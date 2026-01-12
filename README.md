# Comments Remover
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-VS%20Code%20%26%20Anti%20Gravity-informational)

**Comments Remover** is a Visual Studio Code or Anti Gravity extension for safely removing comments from **HTML, CSS, JavaScript, and PHP** files without damaging code structure, indentation, or readability.

Built with a safety-first approach, this extension is ideal for production cleanup and legacy project refactoring.

---

## Features
- HTML comment removal `<!-- -->`
- CSS block comment removal `/* */`
- JavaScript comment removal:
  - Block comments `/* */`
  - Safe single-line comments `//` (does not break URLs or strings)
- PHP comment removal `/* */`, `//`, `#`
- Preserves brackets, indentation, and formatting
- Normalizes spacing (max one empty line between blocks)
- No external dependencies
---

## Supported Languages
- HTML
- CSS
- JavaScript
- PHP
---

## Installation From VSIX (Manual)
1. Download the `.vsix` file or click here <a href="https://github.com/wafarifki/comments-remover/raw/refs/heads/main/comments-remover-1.0.0.vsix" target="_blank">comments-remover-1.0.0.vsix</a>
2. Open VS Code or Anti Gravity
3. Go to Extensions → `...` → **Install from VSIX**
4. Select the file and click install
---

## How to Use
1. Open a supported file in VS Code or Anti Gravity
2. Press `Ctrl + Shift + P`
3. Select **Comments Remover: Remove All Comments**
4. Comments are removed instantly and safely
---

## Why Comments Remover?
Many comment-stripping tools are too aggressive and can break real-world JavaScript code. **Comments Remover** focuses on stability and correctness, making it safe for production environments.

---

## License
This project is licensed under the **MIT License**

---

## Contributions
Issues and pull requests are welcome.  
Your feedback helps improve this project.
