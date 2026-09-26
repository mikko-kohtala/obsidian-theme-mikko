# Mikko Obsidian Theme

Obsidian CSS theme based on the Atom editor color scheme. No build system — edit `theme.css` directly and Obsidian hot-reloads changes.

## Conventions

- When adding color variables, update **both** `.theme-dark` and `.theme-light`
- Shared (non-color) variables go in the combined `.theme-dark, .theme-light` selector
- Prefer overriding Obsidian CSS variables over writing complex selectors; check the [CSS variables reference](https://docs.obsidian.md/Reference/CSS+variables/CSS+variables) first (more references, including the file variables such as `--file-line-width`: `docs/obsidian-css-references.md`)
- Code syntax highlighting uses `!important` for consistency
- Custom additions are commented with `/* Mikko: ... */`
