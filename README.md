# Kagi Claude Theme

A warm, cozy custom CSS theme for [Kagi Search](https://kagi.com) inspired by Claude Desktop's aesthetic. Features a rich brown dark mode with orange accents and a soft monochromatic light mode.

## Screenshots

### Dark Mode
#### Home
![Dark mode home](images/dark-home.png)

#### Results
![Dark mode results](images/dark-results.png)

### Light Mode
#### Home
![Light mode home](images/light-home.png)

#### Results
![Light mode results](images/light-results.png)

## Features

- **Dark mode**: Warm brown tones (`#2F2B26`) with vibrant orange accents (`#D97706`)
- **Light mode**: Soft monochromatic grays for a gentle, low-contrast experience based on [Cidian – Mandarin Dictionary's](https://cidian.co) Light theme
- **Default mode**: Untouched — Kagi's native theme
- Clean, minimal UI adjustments for Dark Mode:
  - Hidden search bar separator, icon-only quick answer button
  - Region filter abbreviation (shows "US" instead of "United States (US)")
  - Styled domain info modal with improved positioning
  - Consistent accent colors across buttons, toggles, links, and dropdowns

## Installation

1. Go to [Kagi Custom CSS Settings](https://kagi.com/settings?p=custom_css)
2. Enable the **Custom CSS** toggle
3. Copy the contents of [`theme.css`](theme.css) and paste it into the text field
4. Click **Apply Custom CSS**
5. Select your preferred theme:
   - **Default**: Kagi's native light theme (no custom styling)
   - **Light**: Soft gray accents
   - **Dark**: Warm brown + orange theme

## Recommended Settings

For best results with the dark theme:
- Set Kagi's base theme to **Dark** or **Moon Dark**

## Color Palette

### Dark Mode
| Role | Color | Hex |
|------|-------|-----|
| Background | ![#2F2B26](https://via.placeholder.com/16/2F2B26/2F2B26?text=+) | `#2F2B26` |
| Background Dark | ![#292521](https://via.placeholder.com/16/292521/292521?text=+) | `#292521` |
| Background Light | ![#3D3832](https://via.placeholder.com/16/3D3832/3D3832?text=+) | `#3D3832` |
| Text | ![#E8E4DF](https://via.placeholder.com/16/E8E4DF/E8E4DF?text=+) | `#E8E4DF` |
| Text Muted | ![#A8A29E](https://via.placeholder.com/16/A8A29E/A8A29E?text=+) | `#A8A29E` |
| Accent | ![#D97706](https://via.placeholder.com/16/D97706/D97706?text=+) | `#D97706` |

### Light Mode
| Role | Color | Hex |
|------|-------|-----|
| Accent | ![#7A7A7A](https://via.placeholder.com/16/7A7A7A/7A7A7A?text=+) | `#7A7A7A` |

## Customization

To customize the colors, edit the CSS variables at the top of the dark theme section:

```css
.theme_moon_dark,
.theme_dark {
  --custom-bg: #2F2B26;
  --custom-bg-dark: #292521;
  --custom-bg-light: #3D3832;
  --custom-text: #E8E4DF;
  --custom-text-muted: #A8A29E;
  --custom-accent: #D97706;
  /* ... */
}
```

## Credits

Designed by **sa**–紗 ([@usants](https://github.com/usants)) and **Anthropic Claude Opus 4.5**

## License

MIT License — feel free to fork, modify, and share!

## Contributing

Issues and pull requests welcome!