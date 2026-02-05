# Universal PDF Converter 📄

A powerful, privacy-focused, client-side web application that converts images, text, code, and data files into a single, formatted PDF document. 

[**🔗 Live Demo**](https://eric-lautanen.github.io/ezPDF/)

## ✨ Features

* **100% Client-Side:** All processing happens in your browser. No files are ever uploaded to a server, ensuring maximum privacy.
* **Multi-Format Support:**
    * **Images:** JPG, PNG, GIF, WebP, BMP (Auto-scaled to fit).
    * **Text & Code:** TXT, MD, HTML, CSS, JS, PY, JSON, XML, and many more. Code files retain formatting.
    * **Data:** Converts CSV and TSV files directly into formatted PDF tables.
* **Smart Clipboard:** Paste text or images directly from your clipboard (Ctrl+V) to add them as pages.
* **Drag & Drop:** Drag files directly into the window or reorder pages via drag-and-drop in the sidebar.
* **Mobile Optimized:** Full mobile support with touch gestures, swipe-to-close menus, and responsive layout.
* **Customization:**
    * Set Document Title.
    * Choose Page Size (A4, Letter, Legal).
    * Toggle Page Numbers.
* **Preview Mode:** Real-time preview of how content will appear before exporting.

## 🛠️ Supported File Types

The converter automatically detects file types and formats them appropriately:

| Category | Extensions |
|----------|------------|
| **Images** | `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, `.bmp` |
| **Code** | `.js`, `.py`, `.html`, `.css`, `.json`, `.xml`, `.java`, `.cpp`, `.php`, `.rb`, `.go`, `.ts`, `.sql`, `.yaml`, etc. |
| **Text** | `.txt`, `.md`, `.rtf`, `.log` |
| **Data** | `.csv`, `.tsv` (Rendered as tables) |

## 🚀 Quick Start

Since this is a single-file application, deployment is incredibly simple.

### Option 1: Run Locally
1. Download `PDFAnything.html`.
2. Open it in any modern web browser (Chrome, Safari, Edge, Firefox).

### Option 2: Host Static
Simply upload the `PDFAnything.html` file to any static host:
* GitHub Pages
* Netlify
* Vercel
* Cloudflare Pages

## 🧩 Technology Stack

* **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+).
* **Styling:** Custom CSS with Dark Mode default, Flexbox/Grid, and Mobile-first media queries.
* **Storage:** In-memory processing (non-persistent for security).

## 🤝 Credits & Acknowledgements

This project was built using the following open-source libraries and AI assistance:

### Libraries
* **[pdfmake](http://pdfmake.org/)** (v0.2.7) - Client-side PDF generation engine.

### Creators
* **Eric Lautanen** - Lead Developer & UI/UX.
* **Claude (Anthropic)** - AI Engineering Partner & Code Assistant.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Note: This application performs heavy processing in the browser. Performance depends on the device's available memory when processing very large high-resolution images.*
