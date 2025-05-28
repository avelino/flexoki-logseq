# Icon Instructions

## Converting SVG to PNG

The theme uses `icon.png` as referenced in `package.json`, but we've provided `icon.svg` for easier editing and scalability.

### Method 1: Online Conversion
1. Go to [CloudConvert](https://cloudconvert.com/svg-to-png) or similar service
2. Upload `icon.svg`
3. Set dimensions to 64x64 pixels
4. Download as `icon.png`
5. Replace the reference in the theme folder

### Method 2: Command Line (ImageMagick)
```bash
convert icon.svg -resize 64x64 icon.png
```

### Method 3: Design Software
- **Figma**: Import SVG, export as PNG (64x64)
- **Sketch**: Import SVG, export as PNG (64x64)
- **Inkscape**: Open SVG, Export PNG (64x64)

### Method 4: Browser Method
1. Open `icon.svg` in a web browser
2. Right-click and "Save image as PNG"
3. Use image editor to resize to 64x64 if needed

## Icon Design Notes

The current icon features:
- **Background**: Warm cream gradient with subtle border
- **Main Element**: Purple "F" for Flexoki in a clean, modern style
- **Accent Dots**: Three colored dots representing the color palette
- **Colors Used**: Direct from Flexoki palette (#5E409D, #205EA6, #24837B, #AF3029)

## Customizing the Icon

To modify the icon:
1. Edit `icon.svg` with any text editor or vector graphics software
2. Change colors by modifying the hex values
3. Adjust paths for different shapes
4. Convert to PNG following the methods above

The icon should be 64x64 pixels for optimal display in Logseq's theme selector.