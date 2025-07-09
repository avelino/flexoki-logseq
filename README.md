<p align="center">
  <a href="https://github.com/avelino/flexoki-logseq">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/avelino/flexoki-logseq/refs/heads/main/icon.svg">
      <img src="https://raw.githubusercontent.com/avelino/flexoki-logseq/refs/heads/main/icon.svg" height="128">
    </picture>
    <h1 align="center">Flexoki Theme for Logseq</h1>
  </a>
</p>

[![Lint](https://github.com/avelino/flexoki-logseq/workflows/Lint/badge.svg)](https://github.com/avelino/flexoki-logseq/actions/workflows/lint.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-2.0.4-blue.svg)](https://github.com/avelino/flexoki-logseq/releases)

A beautiful, warm theme for Logseq inspired by Steph Ango's [Flexoki color scheme](https://stephango.com/flexoki). Designed for comfort and productivity with paper-like colors that are easy on the eyes.

![Flexoki Theme](./flexoki-theme.png)

## Features

- 🎨 **Warm Color Palette**: Paper-inspired colors that reduce eye strain
- 🌙 **Dark & Light Mode**: Seamless switching between themes
- 📝 **Clear Typography**: IBM Plex Sans for excellent readability
- 📱 **Mobile Friendly**: Works great on all devices
- ♿ **Accessible**: WCAG compliant with good contrast ratios
- ⚡ **Performance**: Smooth animations and fast loading

## Installation

### Marketplace (Recommended)
1. Open Logseq → **Settings** → **Features** → **Themes**
2. Click **"Marketplace"**
3. Search for **"Flexoki Theme"**
4. Click **"Install"** and select it from the dropdown

### Manual Installation
1. Download this repository
2. Copy the `logseq-flexoki-theme` folder to your Logseq plugins directory:
   - **Windows**: `%APPDATA%\Logseq\plugins\`
   - **macOS**: `~/Library/Application Support/Logseq/plugins/`
   - **Linux**: `~/.config/Logseq/plugins/`
3. Restart Logseq and select the theme

### Custom CSS
1. Copy the contents of `flexoki-theme.css`
2. Go to **Settings** → **General** → **Custom theme**
3. Paste the CSS and restart Logseq

## Customization

The theme uses CSS variables that you can easily customize:

```css
:root {
  --flexoki-blue: #your-color;     /* Change accent color */
  --flexoki-space-lg: 20px;        /* Adjust spacing */
  --flexoki-radius-md: 8px;        /* Modify border radius */
}
```

## What's Included

✅ Enhanced typography and spacing  
✅ Improved code syntax highlighting  
✅ Better form and button styling  
✅ Responsive design for mobile  
✅ Custom bullet points and checkboxes  
✅ Plugin-compatible styling  

## Development

### Code Quality
This project uses [stylelint](https://stylelint.io/) to ensure consistent CSS code quality. The linting runs automatically on every push and pull request via GitHub Actions.

#### Local Development
```bash
# Install dependencies
npm install

# Run lint check
npm run lint

# Auto-fix linting issues
npm run lint:fix

# Detailed lint report
npm run lint:check
```

#### VS Code Integration
Install the recommended extensions for the best development experience:
- [stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)

## Credits

- **Color Scheme**: [Flexoki](https://stephango.com/flexoki) by Steph Ango
- **Font**: [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans)
- **Built for**: [Logseq](https://logseq.com/)

## License

MIT License - Feel free to modify and share!

---

*Transform your note-taking with Flexoki's warm, comfortable design.*
