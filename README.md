# 🖨️ Ultimate Printer Diagnostic Tool (Web-Based A4 Vector Suite)

<p align="center">
  <img src="https://img.shields.io/badge/Format-Pure%20HTML5%20%7C%20CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/Paper%20Size-A4%20Vector%20Sharp-007ACC?style=for-the-badge" alt="A4 Paper">
  <img src="https://img.shields.io/badge/Platform-Browser%20Native%20Print-4CAF50?style=for-the-badge" alt="Browser Native">
  <a href="https://www.instagram.com/c.wijaya.t">
    <img src="https://img.shields.io/badge/Instagram-@c.wijaya.t-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="MIT License">
</p>

A comprehensive, zero-dependency, single-file printer calibration and diagnostic suite styled with a sleek retro-terminal dark aesthetic. Designed for printer technicians, print shops, and enthusiasts to verify ink density, printhead alignment, typography sharpness, and mechanical feed accuracy directly from any web browser without downloading heavy or blurry PDF test sheets.

<p align="center">
  <b>Created with ❤️ by <a href="https://github.com/rcwpt">rcwpt</a></b> • 
  <b>Follow on Instagram: <a href="https://www.instagram.com/c.wijaya.t">@c.wijaya.t</a></b>
</p>

---

## 🚀 Live Demo & Instant Launch

Run the diagnostic test directly in your browser:

👉 **[Launch Printer Test Ultimate](https://rcwpt.github.io/printertestultimate/)**  
*(Short URL: **[tinyurl.com/rcwpt-print](https://tinyurl.com/rcwpt-print)**)*

> **Auto-Print URL Parameter:**  
> You can trigger the native print dialog automatically on load by appending `?autoprint=1` or selecting a specific page with `?page=1` (e.g. `https://rcwpt.github.io/printertestultimate/?page=1&autoprint=1`).

---

## 📋 Why This Tool?

Most printable test pages found online are:
- Low-resolution raster images (JPEG/PNG) that produce blurry test lines.
- Heavy PDF files that require third-party viewers or external software.
- Hardcoded without margin awareness, causing edge clipping or distortion.

**Printer Test Ultimate** is written in pure vector HTML & CSS with fine millimeter calculations. It features a dedicated `@media print` engine that strips away the screen UI and formats every element with sub-pixel sharpness specifically calibrated for standard **A4 paper**.

---

## ✨ Specialized Diagnostic Pages

The suite includes **4 specialized diagnostic test sheets**:

```
[ Sheet 1: Primary Ink Saturation & Nozzles ]
├── 100% CMYK Primary Solid Blocks (Cyan, Magenta, Yellow, Black)
├── 100% RGB High-Saturation Secondary Blocks (Red, Green, Blue)
├── 2D Full Colour Spectrum Gradient Map
└── High-Frequency Nozzle Check Matrix (Detects clogged micro-jets & banding)

[ Sheet 2: Precision Geometry & Paper Feed ]
├── Edge-to-Edge 1mm Alignment Millimeter Grid
├── 4-Corner Precision Registration Marks (Detects mechanical skew / paper drift)
├── Center Crosshair & Concentric Reference Circles
└── Diagonal 45-degree Linearity Rulers

[ Sheet 3: Typography, Sharpness & Bleed ]
├── Micro-Font Scaling Ladder (6pt Micro up to 72pt Display)
├── Monospace Character Matrix (Verifies dot pitch and kerning uniformity)
├── High-Density 1D Barcode & QR-style calibration lines
└── Inverse High-Contrast Box (White text on black solid to test ink bleed)

[ Sheet 4: Dithering, Halftones & Radial Burst ]
├── 0% to 100% Continuous CMYK Grayscale & Color Ramps
├── 360-degree Radial Starburst (Tests optical resolution and aliasing)
└── Halftone Screening Steps (Detects printhead banding & dithering gaps)
```

---

## ⚙️ Recommended Browser Print Settings

For optimal diagnostic accuracy, configure your browser print preview (Chrome, Edge, or Brave recommended):

1. **Destination:** Select your physical printer (e.g., *Epson L-Series, Canon PIXMA, HP Smart Tank, Brother*).
2. **Paper size:** `A4`
3. **Margins:** `None` or `Default`
4. **Scale:** `100%` / `Default` (Do not select "Fit to printable area" to preserve 1mm true geometry).
5. **Options:** 
   - [x] **Background graphics** (MUST be checked to print solid color blocks).
   - [ ] Headers and footers (Uncheck to keep test sheets pristine).

---

## 🔗 Seamless Integration with Epson Resetter Suite

This diagnostic tool is integrated as the official post-reset verification tool for the **[Epson Resetter All-In-One Suite](https://github.com/rcwpt/epson-resetter-suite)**.

After clearing the **Waste Ink Pad Counter** on an Epson EcoTank printer:
1. Power cycle the printer.
2. Launch **Printer Test Ultimate** via the resetter terminal menu or web link.
3. Print **Page 1** to immediately inspect whether ink flow and nozzle nozzles are firing cleanly after counter initialization.

---

## 💻 Local Setup

If you prefer to run offline:

```bash
git clone https://github.com/rcwpt/printertestultimate.git
cd printertestultimate
```
Simply double-click **`index.html`** to open in your favorite web browser.

---

## 👤 Author & Credits

- **Author**: [rcwpt](https://github.com/rcwpt)
- **Instagram**: [@c.wijaya.t](https://www.instagram.com/c.wijaya.t)
- **Watermark**: *Created with love by rcwpt*

Contributions and feature suggestions are always welcome! Feel free to open an issue or connect on Instagram.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
