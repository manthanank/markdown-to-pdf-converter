# 📄 Markdown to PDF Studio & Converter

[![Deploy to GitHub Pages](https://github.com/manthanank/markdown-to-pdf-converter/actions/workflows/deploy.yml/badge.svg)](https://github.com/manthanank/markdown-to-pdf-converter/actions/workflows/deploy.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-indigo?style=flat&logo=github)](https://manthanank.github.io/markdown-to-pdf-converter/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Zero Backend](https://img.shields.io/badge/Backend-100%25%20Client--Side-emerald)](#privacy--security)

A sleek, modern, in-browser Markdown editor and PDF compiler. Features real-time live preview, bi-directional synchronized scrolling, GitHub Flavored Markdown (GFM), KaTeX mathematical formulas, multi-language syntax highlighting, physical paper sheet simulation (A4 / US Letter), and one-click PDF generation.

🌐 **Live Demo:** [https://manthanank.github.io/markdown-to-pdf-converter/](https://manthanank.github.io/markdown-to-pdf-converter/)

---

## ✨ Features

- **⚡ Real-Time Markdown Compilation**: Powered by Marked.js supporting GitHub Flavored Markdown (tables, checklists, blockquotes, inline formatting).
- **📐 KaTeX Math Typesetting**: Instant rendering of inline LaTeX equations (`$E=mc^2$`) and display block equations (`$$\int_{-\infty}^{+\infty} e^{-x^2} dx = \sqrt{\pi}$$`).
- **🎨 Syntax Highlighting**: Highlight.js syntax highlighting for TypeScript, JavaScript, HTML, SCSS, Python, Bash, JSON, and automatic language detection.
- **🔄 1:1 Synchronized Scrolling**: Bi-directional scroll tracking keeping your position in sync between raw source text and rendered document preview.
- **📄 Print & Paper Simulation**: 
  - True-to-scale physical sheet simulation on screen.
  - Page formats: **A4** and **US Letter**.
  - Configurable page margins: **12mm**, **20mm**, **28mm**.
  - Adjustable body font sizes (13px, 15px, 17px).
  - Built-in document themes: **Modern Clean**, **Academic**, and **Monospace**.
- **📑 Document Break Utilities**: Insert manual page breaks with `<!-- page-break -->` to precisely control page breaks before export.
- **🛠️ Format & Fix Preprocessor**: Built-in state-machine parser that cleans up pasted notes, repairs heading hierarchy, auto-fences loose code snippets, and escapes loose HTML tags.
- **📑 Pre-built Templates**:
  - 🎓 Academic Research Survey
  - 💼 Executive Resume / CV
  - 📖 API SDK Developer Reference Documentation
  - 📝 Markdown & Math Quick Reference Cheat Sheet
- **📥 Import & Autosave**:
  - Import existing `.md`, `.markdown`, or `.txt` files directly.
  - Automatic `localStorage` persistence so you never lose your draft on page reload.
- **🖨️ Dual PDF Export**:
  - **Export PDF Button**: Direct client-side vector-rendered PDF download using `html2pdf.js`.
  - **Print Button**: Native browser print dialog with custom `@media print` styling for maximum printer fidelity.
- **📱 Responsive Layout**: Seamless support across desktop, tablet, and mobile with dedicated Edit / Preview / Split tab switching.
- **🔒 100% Client-Side & Private**: Your text never leaves your browser. Zero tracking, zero server calls, zero risk of data leaks.

---

## 🚀 Quick Start

### Option 1: Use the Live Web App
Visit [https://manthanank.github.io/markdown-to-pdf-converter/](https://manthanank.github.io/markdown-to-pdf-converter/) directly in any modern browser (Chrome, Edge, Firefox, Safari).

### Option 2: Run Locally

No build tools or backend servers are required!

1. **Clone the repository:**
   ```bash
   git clone https://github.com/manthanank/markdown-to-pdf-converter.git
   cd markdown-to-pdf-converter
   ```

2. **Open in your browser:**
   - Double-click `index.html` to open it directly in your browser.
   - Or start a local lightweight web server:
     ```bash
     npx serve .
     # or
     python -m http.server 8000
     ```

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| <kbd>Ctrl</kbd> / <kbd>Cmd</kbd> + <kbd>B</kbd> | Toggle Bold text (`**text**`) |
| <kbd>Ctrl</kbd> / <kbd>Cmd</kbd> + <kbd>I</kbd> | Toggle Italic text (`*text*`) |
| <kbd>Ctrl</kbd> / <kbd>Cmd</kbd> + <kbd>P</kbd> | Trigger Browser Print Dialog |
| <kbd>Tab</kbd> | Insert 2-space indentation |

---

## 🗂️ Project Structure

```text
markdown-to-pdf-converter/
├── .github/
│   └── workflows/
│       └── deploy.yml              # GitHub Actions automated deployment to GitHub Pages
├── index.html                      # Main single-page application (SPA)
├── markdown_to_pdf_converter.html  # Standalone app copy
├── package.json                    # Project metadata & npm helper scripts
├── LICENSE                         # MIT License
├── .gitignore                      # Git ignore rules
└── README.md                       # Comprehensive documentation
```

---

## 🛠️ Built With

- [Tailwind CSS](https://tailwindcss.com/) - Utility-first styling and responsive UI
- [Marked.js](https://marked.js.org/) - Blazing-fast Markdown parser & compiler
- [KaTeX](https://katex.org/) - Fast math typesetting engine for LaTeX
- [Highlight.js](https://highlightjs.org/) - Code syntax highlighter
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) - HTML to vector PDF generation engine
- [Lucide Icons](https://lucide.dev/) - Modern and crisp icon set

---

## 📄 License

This project is open-source and released under the [MIT License](LICENSE).
Feel free to use, modify, and distribute it in personal or commercial projects.
