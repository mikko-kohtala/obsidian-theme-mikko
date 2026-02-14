# Mikko Obsidian Theme

Obsidian CSS theme based on the Atom editor color scheme. No build system — edit `theme.css` directly and Obsidian hot-reloads changes.

## Files

- `manifest.json` — theme metadata (name, version, minAppVersion)
- `theme.css` — all theme styles (~361 lines)

## Key Design Decisions

- `--file-line-width: 1100px` — wider than Obsidian's 700px default, applies to both editing and preview modes
- Accent-colored list markers: `--list-marker-color: var(--text-accent)`
- HSL-based accent color: `--accent-h`, `--accent-s`, `--accent-l` for dynamic color calculations
- Tags styled with `--yellow` color
- Transparent tab/divider borders for a cleaner look

## Conventions

- When adding color variables, update **both** `.theme-dark` and `.theme-light`
- Shared (non-color) variables go in the combined `.theme-dark, .theme-light` selector
- Prefer overriding Obsidian CSS variables over writing complex selectors
- Code syntax highlighting uses `!important` for consistency
- Custom additions are commented with `/* Mikko: ... */`

## Obsidian CSS Reference

When working on this theme, consult these references for available CSS variables and best practices:

- **CSS Variables (full reference)**: https://docs.obsidian.md/Reference/CSS+variables/CSS+variables
- **About Styling (overview)**: https://docs.obsidian.md/Reference/CSS+variables/About+styling
- **Editor > File variables** (`--file-line-width` etc.): https://docs.obsidian.md/Reference/CSS+variables/Editor/File
- **Build a Theme (guide)**: https://docs.obsidian.md/Themes/App+themes/Build+a+theme
- **DeepWiki comprehensive reference**: https://deepwiki.com/obsidianmd/obsidian-developer-docs/3.3-css-variables-reference
- **Developer docs source (GitHub)**: https://github.com/obsidianmd/obsidian-developer-docs
- **Style Settings plugin**: https://github.com/mgmeyers/obsidian-style-settings

## Obsidian CSS Variable Categories

Obsidian exposes 400+ CSS variables organized into these categories:

- **Foundations**: Colors, Typography, Spacing, Borders, Radiuses, Cursor, Icons, Layers
- **Components**: Button, Checkbox, Modal, Navigation, Tabs, Text input, Toggle, etc.
- **Editor**: File, Headings, Code, Blockquote, Callout, Link, List, Table, Tag, etc.
- **Plugins**: Canvas, File explorer, Graph, Search
- **Window**: Divider, Ribbon, Scrollbar, Status bar, Workspace
