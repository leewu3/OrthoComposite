# Orthodontic Composite Creator

This is an independent experimental project by a solo developer. I created this out of a desire to have a professional looking composite creator that is just as efficient as the expensive proprietary programs like Dolphin, but without the cost. It is a professional desktop application for creating orthodontic photo composites with drag-and-drop image placement, editing tools, and high-quality PDF/image export.

_**[Download link](https://github.com/leewu3/OrthoComposite/releases/download/v1.0/OrthoComposite.exe) for Windows executable.**_

## Installation Notes & Security

Why you might see a warning:
Because this is a new, independent project, the Windows SmartScreen filter may flag the file as "unrecognised." This is a standard security measure for software that hasn't yet built up a "reputation" with Microsoft or been signed with an expensive corporate certificate. 

If you are still worried check the hash and make sure it hasn't been tampered with: SHA-256 25e81f0e2afc02a88010ed3975adba46aad90081e0733dd12146824d815347f1

Here's the virustotal.com scan URL: https://www.virustotal.com/gui/file/25e81f0e2afc02a88010ed3975adba46aad90081e0733dd12146824d815347f1

**How to install:**

- Click Download (if your browser asks, select "Keep" or "Trust").

- Run the installer.

- If the blue "Windows protected your PC" box appears, click "More Info" and then select "Run anyway."


## Features

- **Drag & Drop** — Drop images directly into any cell of the 3×3 grid
- **Image Editing** — Rotate (smooth slider preview), mirror (H/V), and crop (rubber-band selection with handles)
- **Patient Info Panel** — Editable Name, DOB, Date, and Status fields in the center cell
- **Practice Logo** — Set your logo in Settings; it appears on every composite
- **High-Quality Export** — Landscape 8.5×11" at 300 DPI as both PNG and PDF
- **Portable Executable** — Available as a Windows executable that doesn't require installation
- **Dark Theme** — Modern, accessible UI with WCAG AA compliant contrast ratios

## Support my work
If this software has improved your practice efficiency, please consider supporting me @ https://buymeacoffee.com/leewu


## Usage Guide

### Adding Images
1. **Drag & drop** image files onto any cell, or
2. **Click** an empty cell to browse for an image, or
3. **Right-click** a cell for the context menu

### Editing Images
- **Double-click** an image to open the full editor (Rotate / Mirror / Crop tabs)
- **Right-click** for quick actions (mirror, rotate 90°, remove)
- **Rotate tab**: Use the slider for precise rotation with live preview; quick buttons for common angles
- **Crop tab**: Click and drag to define crop area; drag corners/edges to resize; drag center to move
- **Brightness & Contrast tab**: Click and drag on each slider to adjust brightness and contrast

### Setting the Logo
1. Go to **Settings → Preferences**
2. Browse for your practice logo image
3. The logo will appear in the center panel of every composite

### Exporting
- **Ctrl+E** — Export as PNG image
- **Ctrl+Shift+E** — Export as PDF
- **Ctrl+Shift+B** — Export both PNG and PDF at once

Output files are landscape 8.5×11" at 300 DPI (3300×2550 pixels).

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| Ctrl+N | New composite |
| Ctrl+E | Export as image |
| Ctrl+Shift+E | Export as PDF |
| Ctrl+Shift+B | Export both |
| Ctrl+Q | Quit |

## Technical Details

- **GUI Framework**: PyQt5
- **Image Processing**: Pillow (PIL)
- **PDF Generation**: ReportLab
- **Packaging**: PyInstaller (single-file portable executable)
- **Output Resolution**: 3300 × 2550 px (300 DPI, 11" × 8.5")


