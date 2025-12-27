# Kanboard Tokyo Night

A dark theme for [Kanboard](https://kanboard.org/) based on the beautiful [Tokyo Night](https://tokyonight.org) color scheme.

## Features

- 🌙 Full dark mode with carefully chosen contrast
- 🎨 Complete coverage of all Kanboard UI components
- ✨ Subtle hover effects and glows
- 📋 Task cards with colored left borders (Trello-style)
- 🔍 Styled Select2 dropdowns and autocomplete fields
- 📜 Custom scrollbars (WebKit browsers)
- 💬 Styled comments, markdown, and text editor


## Installation

1. Log in to Kanboard as an administrator
2. Go to **Settings** → **Application Settings**
3. Scroll down to **Custom Stylesheet**
4. Copy the entire contents of [`kanboard-tokyo-night.css`](kanboard-tokyo-night.css)
5. Paste into the Custom Stylesheet field
6. Click **Save**

That's it! The theme will apply immediately.

## Color Palette

This theme uses the Tokyo Night color palette:

| Color | Hex | Usage |
|-------|-----|-------|
| Background | `#1a1b26` | Main background |
| Surface | `#24283b` | Cards, header |
| Input | `#1f2335` | Input fields |
| Border | `#414868` | Borders |
| Muted | `#565f89` | Muted text |
| Text | `#a9b1d6` | Primary text |
| Bright | `#c0caf5` | Headings |
| Blue | `#7aa2f7` | Primary accent |
| Cyan | `#7dcfff` | Links (hover) |
| Purple | `#bb9af7` | Visited links |
| Green | `#9ece6a` | Success |
| Red | `#f7768e` | Danger |
| Yellow | `#e0af68` | Warning |
| Orange | `#ff9e64` | Orange accent |
| Teal | `#73daca` | Teal accent |

## Task Colors

Task card colors use a left-border accent style while maintaining the dark card background:

| Kanboard Color | Accent |
|----------------|--------|
| Yellow | `#e0af68` |
| Blue | `#7aa2f7` |
| Green | `#9ece6a` |
| Purple | `#bb9af7` |
| Red | `#f7768e` |
| Orange | `#ff9e64` |
| Cyan | `#7dcfff` |
| Teal | `#73daca` |

## Compatibility

- Tested with Kanboard 1.2.x
- Works in all modern browsers
- Custom scrollbars only visible in WebKit browsers (Chrome, Safari, Edge)

## Customization

The theme uses CSS custom properties (variables) at the `:root` level. You can easily adjust colors by modifying the variables at the top of the file.

```css
:root {
    --body-background-color: #1a1b26;
    --header-background-color: #24283b;
    --link-color-primary: #7aa2f7;
    /* ... etc */
}
```

## Credits

- Color palette by [Enkia](https://github.com/enkia/tokyo-night-vscode-theme)
- [Kanboard](https://kanboard.org/) by Frédéric Guillot

## Related Themes

Love Tokyo Night? Check out ports for other apps:
- [TokyoNight.org](https://tokyonight.org)

## License

MIT License - feel free to use, modify, and distribute.

## Contributing

Found a bug or missing style? PRs welcome! Please include a screenshot showing the issue.

---

⭐ If you find this theme useful, consider giving it a star!
