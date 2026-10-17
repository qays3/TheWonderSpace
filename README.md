# TheWonderSpace

A calm, cosmic theme for [Obsidian](https://obsidian.md), built around soft purples.

Not loud, not neon, not tiring. Just a quiet, comfortable space to think and write in, like looking up at a clear night sky.

> Screenshot goes here: `![TheWonderSpace](screenshot.png)`

## Why "Wonder"?

The name comes from the feeling of looking at the stars: calm, curious, and a little amazed. The theme tries to give you that same feeling while you work. Deep violet backgrounds, gentle lavender text, and small touches of warm gold and soft cyan, like distant stars.

## Features

- **Calm purple palette.** Deep indigo-violet in dark mode, soft lilac in light mode.
- **Easy on the eyes.** Contrast is balanced for long writing sessions, with no pure black and no pure white.
- **Lavender heading scale.** Headings shift gently from light to deeper violet, so structure is clear without being harsh.
- **Starry graph view.** Nodes and links are styled like stars and constellations.
- **Dark and light modes.** *Night Sky* (dark) and *Soft Dawn* (light).
- **Rounded, soft shapes.** Code blocks, quotes, and buttons use smooth corners.
- **Built on Obsidian's CSS variables.** Stable across updates and easy to customize.

## Color palette

### Night Sky (dark)

| Role | Color |
|---|---|
| Background | `#1b1730` |
| Sidebar | `#15122a` |
| Text | `#e7e2f7` |
| Accent | `#a78bfa` |
| Stars (highlights) | `#f0d682`, `#8fd3e0` |

### Soft Dawn (light)

| Role | Color |
|---|---|
| Background | `#fbf9ff` |
| Sidebar | `#f1ecfb` |
| Text | `#2c2547` |
| Accent | `#7c5cd6` |

## Installation

### From the community themes (after approval)

1. Open **Settings → Appearance**.
2. Under **Themes**, click **Manage**.
3. Search for **TheWonderSpace** and click **Install and use**.

### Manual installation

1. Download `theme.css` and `manifest.json` from the [latest release](https://github.com/qays3/TheWonderSpace/releases/latest).
2. In your vault, create the folder `.obsidian/themes/TheWonderSpace/`.
3. Put both files inside it.
4. In Obsidian, go to **Settings → Appearance → Themes**, refresh, and select **TheWonderSpace**.

## Customization

You can tweak the theme with a CSS snippet in `.obsidian/snippets/`. For example, to change the accent color:

```css
.theme-dark {
  --interactive-accent: #c084fc;
  --text-accent: #d8b4fe;
}
```

## Recommended settings

- Set **Appearance → Base color scheme** to *Adapt to system* so the theme follows your day and night.
- The theme uses **Inter** for text. If it isn't installed, it falls back to your system font.

## Roadmap

- [ ] Callouts styling
- [ ] Tabs and status bar polish
- [ ] Canvas colors
- [ ] Table and checkbox styling
- [ ] Mobile testing
- [ ] Style Settings plugin support

## Contributing

Found a bug or have an idea? Open an [issue](https://github.com/qays3/TheWonderSpace/issues) or a pull request. Screenshots of what looks off are very helpful.

## License

[MIT](LICENSE)