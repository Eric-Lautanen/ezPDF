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
* **Mobile Optimized:** Full mobile support with touch gestures, side-by-side header buttons, and responsive layout.
* **Customization:** Set Document Title, Page Size (A4, Letter, Legal), and Toggle Page Numbers.

## 🛠️ Supported File Types

| Category | Extensions |
|----------|------------|
| **Images** | `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, `.bmp` |
| **Code** | `.js`, `.py`, `.html`, `.css`, `.json`, `.xml`, `.java`, `.cpp`, `.php`, `.rb`, `.go`, `.ts`, `.sql`, `.yaml`, etc. |
| **Text** | `.txt`, `.md`, `.rtf`, `.log` |
| **Data** | `.csv`, `.tsv` (Rendered as tables) |

## 🚀 How to Download & Run (Offline Mode)

This application is entirely self-contained in a single file. You can save it to your device and use it anywhere—even without an internet connection.

### 1. Download from GitHub
1.  On the main repository page, click on the file named `index.html`.
2.  On the top right of the file content area, look for the **"Download raw file"** button.
3.  Choose a location on your computer to save it.

### 2. Rename the File
* The file will likely save as `index.html`. 
* You can rename it to something more descriptive, like `PDFConverter.html` or `ezPDF.html`. 
* **Note:** Ensure the name ends in `.html`.

### 3. How to Open
* Simply **double-click** the file you just saved.
* It will open in your web browser (Chrome, Firefox, Safari, or Edge).
* You are now running the app locally and privately!

## 🧩 Technology Stack

* **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+).
* **Self-Contained:** All libraries (like pdfmake) are bundled inside the HTML file to allow for zero-dependency offline use.
* **Privacy:** All processing is done in-memory; nothing is ever sent to a server.

## 🤝 Credits & Acknowledgements

This project was built using the following open-source libraries and AI assistance:

### Libraries
* **[pdfmake](http://pdfmake.org/)** (v0.2.7) - Client-side PDF generation engine (embedded inline).

### Creators
* **Eric Lautanen** - Lead Developer & UI/UX.
* **Claude & Gemini** - AI Engineering Partners.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Note: Large high-resolution images require significant browser memory. For best performance on mobile, try to limit the number of ultra-high-res photos in a single export.*
