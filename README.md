# Universal PDF Converter 📄

A powerful, privacy-focused, **100% offline-capable** client-side web application that converts images, text, code, and data files into a single, formatted PDF document. 

[**🔗 Live Demo**](https://eric-lautanen.github.io/ezPDF/)

## ✨ Features

* **100% Client-Side & Offline:** All processing happens in your browser. All required libraries are embedded directly within the file. Once downloaded, you can use it without an internet connection. No files are ever uploaded to a server, ensuring maximum privacy.
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

## 🚀 How to Download & Run (Offline Mode)

Since this application is a single-file solution with all libraries contained within, you can run it entirely without an internet connection.

### 1. Download from GitHub
1.  On the GitHub repository, click on the file named `index.html`.
2.  Look for the **Download raw file** button (the downward arrow icon ⬇️ in the top right of the file view).
3.  Right-click the button and select **"Save Link As..."** (or simply click it to download).

### 2. Rename the File
* The file will download as `index.html`. 
* You can rename this to anything you like (e.g., `PDFConverter.html` or `UniversalPDF.html`) as long as it keeps the **.html** extension.

### 3. Open & Use
* Simply **double-click** the file on your computer.
* It will open in your default web browser (Chrome, Firefox, Edge, or Safari).
* **Privacy Note:** You can even turn off your Wi-Fi before opening it—the app will work perfectly because it is completely self-contained.

## 🧩 Technology Stack

* **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+).
* **Self-Contained:** All libraries (like pdfmake) are bundled inside the HTML file to allow for zero-dependency offline use.
* **Privacy:** In-memory processing (non-persistent for security).

## 🤝 Credits & Acknowledgements

This project was built using the following open-source libraries and AI assistance:

### Libraries
* **[pdfmake](http://pdfmake.org/)** (v0.2.7) - Client-side PDF generation engine (embedded directly in the file).

### Creators
* **Eric Lautanen** - Lead Developer & UI/UX.
* **Claude (Anthropic) & Gemini (Google)** - AI Engineering Partners & Code Assistants.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Note: This application performs heavy processing in the browser. Performance depends on the device's available memory when processing very large high-resolution images.*
