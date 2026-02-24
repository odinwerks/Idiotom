# Idiotom

An atom visualizer. Built it because I needed decent atom drawings for some physics textbook illustrations.

## What it does

- Visualizes atoms with protons, neutrons, and electrons
- Interactive periodic table - click any element to visualize it
- Dark/light mode toggle
- Electron shell visualization
- Cation/anion support (add or remove electrons)
  - The UI displays the charge state (neutral atom, cation, or anion) with color-coded labels
  - The atom drawing updates to reflect the electron configuration
- Shows atomic number (Z), mass number (A), and charge state
- SVG/PNG/BMP export with customizable size, DPI, background color, and transparency

## Screenshots

![Gold](images/Aurum.png)
![Light mode](images/light-mode.png)

## Usage

Open `Idiotom.html` in any browser. No install needed.

## Export

Click the ⬇ button to export. Options:
- **Format**: SVG, PNG, or BMP
- **Transparent background**: Available for PNG (disabled for BMP)
- **Background color**: Custom color picker with hex input
- **Size**: Width/height in cm (1:1 ratio)
- **DPI**: Resolution - 300 for print, 72 for screen

SVG exports with a white background by default.

## Known limitations

- Electrons are positioned roughly using electron configuration rules, not quantum mechanics

## License

Make a nuclear bomb if you wanna, just don't blow yourself up <3
