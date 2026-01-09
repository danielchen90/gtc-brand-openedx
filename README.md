# Mary Banks Global Training Center - Brand Package

Custom branding package for Open edX MFEs (Micro-Frontends) for Mary Banks Global Training Center.

## 🎨 Brand Identity

**Organization:** Mary Banks Global Training Center
**Tagline:** Transform your calling into powerful ministry impact
**Primary Color:** #EAB308 (Gold)
**Secondary Color:** #f5f5f5 (Light gray)
**Font:** Arial, Helvetica, sans-serif

## 📦 Package Contents

```
gtc-brand-openedx/
├── package.json              # NPM package configuration
├── logo.png                  # GTC logo (main)
├── logo-white.png            # GTC logo (white version)
├── favicon.ico               # Browser favicon
├── paragon/
│   ├── _variables.scss       # SCSS variables (colors, fonts, spacing)
│   ├── _overrides.scss       # Component style overrides
│   ├── core.scss             # Core styles
│   └── tokens/               # Design tokens
└── README.md                 # This file
```

## 🚀 Usage

This package is automatically installed in Open edX MFEs via the Tutor plugin `tutor-contrib-gtc-branding`.

### Installation in MFE

```bash
npm install '@edx/brand@git+https://github.com/YOUR_USERNAME/gtc-brand-openedx.git'
```

MFEs will automatically detect and use this package for branding.

## 🎨 Customization

### Colors

Edit `paragon/_variables.scss` to change colors, fonts, spacing, etc.

### Component Styles

Edit `paragon/_overrides.scss` to override specific component styles.

## 🔧 Development

```bash
npm run build          # Build all
npm run build:watch    # Watch mode
```

## 📝 Making Changes

1. Edit files in `paragon/` directory
2. Commit and push to GitHub
3. Rebuild MFE images on server:
   ```bash
   sudo tutor images build --no-cache mfe
   sudo tutor local restart mfe
   ```

## 🌈 Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Primary Gold | `#EAB308` | Buttons, accents, links |
| Gold Hover | `#CA9A06` | Button hover states |
| Dark Text | `#171717` | Text on light/gold backgrounds |
| Secondary | `#f5f5f5` | Backgrounds, secondary elements |
| Border | `#e5e5e5` | Borders, dividers |
| Error | `#dc2626` | Error messages |
| Success | `#16a34a` | Success messages |

## 📞 Support

**Contact:** daniel@mbmonline.global  
**Website:** https://mbmonline.global

## 📄 License

Proprietary to Mary Banks Global Training Center.
