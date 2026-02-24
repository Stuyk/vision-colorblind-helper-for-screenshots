# The Vision Engine

Color-Blind Game Dev Assistant — inspect UI screenshots for perceptual issues.

Main page: https://stuyk.github.io/vision-colorblind-helper-for-screenshots/

## Summary

The Vision Engine is a lightweight browser-based tool for analyzing UI screenshots with an emphasis on accessibility for color-blind users. It provides a pixel inspector, perceptual LCH color readouts, color-blind simulation modes, a magnifier, and a small palette saver/exporter.

## Features

- Drag & drop, paste, or upload screenshots
- Pixel-level color readout (RGB → LCH)
- Accessibility rating hints (white/yellow checks, confusion zones)
- Color-blind simulation filters: Protanopia, Deuteranopia, Tritanopia, Grayscale, Edge
- Magnifier preview on hover
- Save up to 5 palette colors and export JSON

## Usage

1. Open `index.html` in a browser (or serve the directory with a static server):

   ```bash
   python -m http.server 8000
   # then open http://localhost:8000
   ```

2. Upload, paste (Ctrl+V), or drag a screenshot into the canvas area.
3. Hover to inspect pixels, click to save colors to the palette, and use the mode buttons to preview color-blind simulations.

## Files

- `index.html` — main app UI and logic

## License

MIT
