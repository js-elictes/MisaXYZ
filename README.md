# RSI MolKit Viewer

**RSI MolKit Viewer** is a lightweight web-based viewer for `.xyz` molecular files, designed for quick and clean 3D visualization using a custom build of [3Dmol.js](https://3dmol.org/).

## Features

- Load and view multiple `.xyz` molecules
- Switch between **stick** and **ball & stick** styles
- Toggle atom **labels** (off, element, or atom number)
- View **molecular formulas** calculated in real time
- Automatically color elements (with metals highlighted)
- Clean, responsive interface with custom UI

## How to Use

1. Open `index.html` in your browser
2. Click **"Open .xyz"** and select your file
3. Use the sidebar to browse and interact with molecules

## Dependencies

- [`3Dmol.js`](https://3dmol.csb.pitt.edu/) (custom minimized build included)
- Local font files (`Inter`) for consistent styling

## Notes

- Supports `.xyz` files with multiple molecule blocks
- Formula display orders atoms as: C, H, then alphabetical

---

Made by RSI for the Roithová Group in 2025
