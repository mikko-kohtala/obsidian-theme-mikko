# Mikko Obsidian Theme

Obsidian CSS theme based on the Atom editor color scheme. No build system — edit `theme.css` directly and Obsidian hot-reloads changes.

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
