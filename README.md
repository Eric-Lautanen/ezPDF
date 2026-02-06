# ezPDF 📄

A powerful, privacy-focused, **100% offline-capable** client-side web application that converts images, text, code, and data files into a single, beautifully formatted PDF document.

[**🔗 Live Demo**](https://eric-lautanen.github.io/ezPDF/)

## ✨ Features

* **100% Client-Side & Offline:** All processing happens in your browser. All required libraries and syntax highlighting themes are embedded directly within the file. Once downloaded, you can use it without an internet connection. No files are ever uploaded to a server, ensuring maximum privacy.
* **Multi-Format Support:**
    * **Images:** JPG, PNG, GIF, WebP, BMP, SVG, TIFF, ICO (Auto-scaled to fit page size).
    * **Code:** 60+ programming languages with syntax highlighting including JavaScript, Python, Java, C/C++, Rust, Go, PHP, Ruby, Swift, Kotlin, and many more. See [full list](#-supported-file-types).
    * **Data:** CSV and TSV files rendered as formatted PDF tables with headers.
    * **Text:** Plain text, Markdown, RTF, and log files.
* **Syntax Highlighting:** Code files are beautifully highlighted with theme support (Light & Dark).
* **Real-Time Preview:** See how your PDF will look before exporting, with live updates as you adjust settings.
* **Paste Text Area:** Quick input area for adding plain text notes and snippets.
* **Drag & Drop:** Drag files directly into the window and drag to reorder pages on sidebar/slideout.
* **Mobile Optimized:** Full mobile support with touch gestures, responsive layout, and optimized scrolling.
* **Extensive Customization:** 
    * Document Title
    * Page Size (A4, Letter, Legal)
    * Headers & Footers (Page Numbers, Titles, or Both)
    * Font Selection (Helvetica, Times New Roman, Courier)
    * Font Size (8pt - 16pt)
    * Code Theme (Light or Dark for syntax highlighting)

## 🛠️ Supported File Types

| Category | Extensions |
|----------|------------|
| **Images** | `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, `.bmp`, `.svg`, `.tiff`, `.ico` |
| **Web** | `.html`, `.htm`, `.xml`, `.xhtml`, `.css`, `.scss`, `.sass`, `.less` |
| **JavaScript/TypeScript** | `.js`, `.jsx`, `.ts`, `.tsx`, `.mjs`, `.cjs`, `.vue`, `.svelte` |
| **Python** | `.py`, `.pyw`, `.pyx`, `.pyi` |
| **Java/JVM** | `.java`, `.kt`, `.kts`, `.scala`, `.groovy` |
| **C/C++** | `.c`, `.cpp`, `.cc`, `.cxx`, `.h`, `.hpp`, `.hxx` |
| **C#/.NET** | `.cs`, `.csx`, `.vb`, `.fs`, `.fsx` |
| **Mobile** | `.swift`, `.m`, `.mm` (Objective-C) |
| **Systems** | `.rs` (Rust), `.go`, `.zig` |
| **Scripting** | `.sh`, `.bash`, `.zsh`, `.fish`, `.bat`, `.cmd`, `.ps1` |
| **Ruby** | `.rb`, `.erb`, `.rake` |
| **PHP** | `.php`, `.phtml`, `.php3`, `.php4`, `.php5` |
| **SQL** | `.sql`, `.mysql`, `.pgsql`, `.plsql` |
| **Functional** | `.hs`, `.elm`, `.ml`, `.ex`, `.exs`, `.erl`, `.clj`, `.cljs` |
| **Data/Config** | `.json`, `.yaml`, `.yml`, `.toml`, `.ini`, `.cfg`, `.conf`, `.properties`, `.csv`, `.tsv` |
| **Other** | `.r`, `.R`, `.lua`, `.vim`, `.diff`, `.patch`, `.dart`, `.dockerfile`, `.makefile`, `.proto`, `.graphql`, `.sol`, and more |
| **Text** | `.txt`, `.md`, `.markdown`, `.rtf`, `.log` |

## 🚀 How to Download & Run (Offline Mode)

This application is entirely self-contained in a single file. You can save it to your device and use it anywhere—even without an internet connection.

### 1. Download from GitHub
1. 👉 [Download ezPDF (index.html)](https://github.com/Eric-Lautanen/ezPDF/raw/main/index.html)
2. Choose a location on your computer to save it.

### 2. Rename the File (Optional)
* The file will likely save as `index.html`. 
* You can rename it to something more descriptive, like `PDFConverter.html` or `ezPDF.html`. 
* **Note:** Ensure the name ends in `.html`.

### 3. How to Open
* Simply **double-click** the file you just saved.
* It will open in your web browser (Chrome, Firefox, Safari, or Edge).
* You are now running the app locally and privately!

## 🎨 Preview Features

* **Sidebar Thumbnails:** Mini syntax-highlighted previews that match the final PDF output
* **Main Preview Area:** Full-size preview with exact PDF rendering including:
  * Syntax-highlighted code with language badges
  * Theme-aware backgrounds (light/dark)
  * Headers and footers (when enabled)
  * Page size visualization
* **Live Updates:** All previews update in real-time when settings change

## 🧩 Technology Stack

* **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **PDF Generation:** [jsPDF](https://github.com/parallax/jsPDF) v2.5.1 with autoTable plugin v3.5.31 (embedded inline)
* **Syntax Highlighting:** [highlight.js](https://highlightjs.org/) (GitHub Light & Dark themes embedded inline)
* **Self-Contained:** All libraries and stylesheets bundled inside the HTML file for zero-dependency offline use
* **Privacy-First:** All processing is done in-memory; nothing is ever sent to a server

## 🐛 Known Issues

- Large files (10MB+) may cause slower preview rendering on older devices
- Some very long code files may need manual page break optimization
- CSV files with irregular column counts may render with slight formatting inconsistencies
- Paste area is for plain text only - code detection works only for uploaded files with code extensions

## 🤝 Credits & Acknowledgements

This project was built using the following open-source libraries and AI assistance:

### Libraries
* **[jsPDF](https://github.com/parallax/jsPDF)** (v2.5.1) - Client-side PDF generation engine
* **[jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable)** (v3.5.31) - Table plugin for jsPDF
* **[highlight.js](https://highlightjs.org/)** - Syntax highlighting for code files

### Creators
* **Eric Lautanen** - Lead Developer & UI/UX
* **Claude (Anthropic)** - AI Engineering Partner
* **Gemini (Google)** - AI Engineering Partner

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 💡 Tips for Best Results

* **Images:** For best quality, use images between 800x600 and 2400x1800 pixels
* **Code Files:** Files with 500+ lines may benefit from being split into multiple pages
* **Tables:** CSV/TSV files render best with fewer than 20 columns
* **Mobile:** Close the sidebar after adding files to maximize preview space
* **Performance:** For large exports (20+ files), consider exporting in smaller batches
* **Text vs Code:** Upload files with proper extensions (.js, .py, etc.) for syntax highlighting - the paste area is for plain text only

---

*Built with ❤️ for privacy-conscious developers and creators who need a simple, powerful PDF tool that works anywhere.*
