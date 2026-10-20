# ⚡ Memify — Meme Studio & Header Editor

> A lightweight, client-side meme generator, header studio, and image editor running entirely in your browser with zero server dependencies.

![Memify Banner](https://img.shields.io/badge/Memify-Meme%20Studio-ffd23f?style=for-the-badge&logo=target&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Pure Vanilla](https://img.shields.io/badge/vanilla-HTML%20%7C%20CSS%20%7C%20JS-orange?style=flat-square)
![Privacy First](https://img.shields.io/badge/privacy-100%25%20Client--Side-green?style=flat-square)

---

## ✨ Features

- 📝 **Meme Headers & Captions**: Add top headers and bottom captions with classic meme fonts (Anton, Arial, Serif, Mono), custom background/text colors, dynamic padding, font size, text alignment, and case conversion.
- 🎨 **Creative Tooling**:
  - **Move**: Reposition any layer, text, or sticker.
  - **Text Layers**: Add floating meme text overlays with high-contrast outlines.
  - **Stickers & Emojis**: Stamp popular emojis directly onto images.
  - **Freehand Drawing**: Doodle and sketch directly over images.
  - **Blur & Censor**: Blur sensitive areas or apply retro pixelation censors.
- 🖼️ **Image Transformations**:
  - Rotate 90° left or right.
  - Flip horizontally.
  - Crop to standard aspect ratios (1:1 Square, 4:5 Portrait, 16:9 Landscape, 9:16 Story).
  - Quick resize scaling (25%, 50%, 75%, 200%).
- 🧪 **Filters & Visual FX**:
  - Grayscale, Sepia, Invert.
  - Pixelate effect.
  - Glitch (chromatic aberration & slice displacement).
  - Deep fry (intense contrast, saturation, and compression artifacts).
- 📁 **Batch Processing & Projects**:
  - **Batch Processing**: Apply top/bottom captions to dozens of images simultaneously and download them in a single ZIP file (`JSZip`).
  - **Project Files**: Save your work-in-progress as `.json` project files and re-open them anytime.
  - **Custom Presets**: Save your favorite styling configurations into browser storage.
- ⚡ **Productivity**:
  - Full Undo / Redo history stack (up to 50 actions).
  - Direct clipboard paste (`Ctrl+V` to load images).
  - One-click copy final meme directly to system clipboard.
  - Export lossless PNGs.
  - Responsive layout for desktop and tablet screens.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| --- | --- |
| `Ctrl + Z` / `Cmd + Z` | Undo last action |
| `Ctrl + Shift + Z` / `Cmd + Shift + Z` | Redo action |
| `Delete` / `Backspace` | Delete selected layer (text, sticker, drawing) |
| `Ctrl + V` / `Cmd + V` | Paste image from clipboard |

---

## 🚀 Getting Started

Since **Memify** is built with pure Vanilla HTML5, CSS3, and JavaScript, no build step or package manager is required!

### Option 1: Open Directly in Browser
Double-click `index.html` or open it with any web browser.

### Option 2: Run with a Local Server
Using Python:
```bash
python -m http.server 3000
```
Or using Node.js / `npx serve`:
```bash
npx serve .
```
Then visit `http://localhost:3000`.

---

## ☁️ Deployment

### Deploy to Vercel
Memify includes a pre-configured `vercel.json` with security headers. Simply run:
```bash
npx vercel
```
or connect your GitHub repository to [Vercel](https://vercel.com).

### Deploy to GitHub Pages
1. Go to your repository on GitHub.
2. Navigate to **Settings** > **Pages**.
3. Under **Branch**, select `main` and root `/`.
4. Click **Save**. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

---

## 🔒 Privacy

All processing is performed **100% locally** on your device using HTML5 Canvas. Your images are never uploaded to any server.

---

## 📄 License

MIT License. Feel free to use, modify, and distribute!
