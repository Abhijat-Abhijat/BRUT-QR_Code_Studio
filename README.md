<div align="center">

# ▣ BRUT® QR STUDIO

### A QR generator with a little more edge.

**Make it. Scan it. Ship it.**

A fast, browser-based QR code generator wrapped in a bold brutalist interface.

<br />

![Static Website](https://img.shields.io/badge/website-static-171717?style=flat-square)
![No Build Step](https://img.shields.io/badge/setup-no%20build-ccff00?style=flat-square&labelColor=171717)
![Runs in Browser](https://img.shields.io/badge/runs-in%20your%20browser-171717?style=flat-square)

</div>

---

## ✳ What is BRUT?

BRUT® QR Studio turns website links into downloadable QR codes—without a complicated workflow. Paste a URL, tune the output, generate your code, and download it as a PNG.

The visual direction is inspired by **modern brutalism**: oversized type, sharp edges, strong borders, hard shadows, and electric-lime details against a warm paper-like background.

## ⚡ Features

| Feature | What it does |
| --- | --- |
| **URL to QR** | Generate a QR code from a website address. |
| **Multiple sizes** | Choose from 200, 300, 400, 500, or 700 px. |
| **Quiet-zone control** | Adjust the margin around the QR code. |
| **PNG export** | Download the generated code for digital or print use. |
| **URL assistance** | Validate the address and add `https://` when the scheme is missing. |
| **Example link** | Try a sample URL to see how it works. |
| **Clear workspace** | Reset the form and start fresh. |
| **Responsive UI** | Use it on desktop, tablet, or mobile. |
| **Accessibility details** | Includes visible keyboard focus and reduced-motion support. |

## ◼ The look

- Warm, off-white paper-inspired background with a subtle dot grid
- Bold black borders and offset shadows
- Acid-lime accents for a high-impact contrast
- Space Grotesk display type paired with Space Mono details
- Clean, responsive layout with straightforward controls

## 🚀 Get started

**No installation. No build tools. Just open the file.**

1. Download or clone the project.
2. Open `brut-qr-studio.html` in a modern browser.
3. Enter a website URL.
4. Choose the image size and quiet-zone margin.
5. Click **Generate QR code**.
6. Click **Download PNG** to save your QR code.

### Optional: run a local server

If Python is installed, run this command from the project folder:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000/brut-qr-studio.html](http://localhost:8000/brut-qr-studio.html).

## 🧱 Built with

- **HTML** — structure
- **CSS** — layout and brutalist styling
- **Vanilla JavaScript** — interactions and validation
- **[QRCode.js](https://github.com/davidshimjs/qrcodejs)** — QR code generation
- **[Google Fonts](https://fonts.google.com/)** — Space Grotesk and Space Mono

> **Heads-up:** QRCode.js and the fonts load from external CDNs, so an internet connection is needed for those resources.

## 📁 Project structure

```text
.
├── brut-qr-studio.html
└── README.md
```

## 🔎 Good to know

- QR codes are generated in your browser; this project does not store your URLs on a server.
- Use a valid `http://` or `https://` destination. A domain entered without a scheme is automatically prefixed with `https://`.
- Always scan-test your QR code before publishing or printing it.
- The chosen output size controls the generated image dimensions; the on-page preview may appear smaller to fit the layout.

## ⛔ Current limitations

- This is a **static, client-side tool**. It does not create trackable or dynamic QR codes.
- There are no accounts, server-side storage, or analytics dashboard.
- QR generation depends on the external QR code library loading successfully.

## 📜 License

No license has been specified yet. Add a `LICENSE` file if you plan to distribute the project and want to define how others may use, modify, or share it.

---

<div align="center">

**DESIGNED TO BE SIMPLE. BUILT TO BE BRUT.**

</div>
