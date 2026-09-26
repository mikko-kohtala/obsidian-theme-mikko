# Mikko Obsidian Theme

Obsidian CSS theme based on the Atom editor color scheme. No build system — edit `theme.css` directly and Obsidian hot-reloads changes.

## Conventions

- When adding color variables, update **both** `.theme-dark` and `.theme-light`
- Shared (non-color) variables go in the combined `.theme-dark, .theme-light` selector
- Prefer overriding Obsidian CSS variables over writing complex selectors
- Code syntax highlighting uses `!important` for consistency
- Custom additions are commented with `/* Mikko: ... */`

## Obsidian CSS Reference

Available CSS variables: https://docs.obsidian.md/Reference/CSS+variables/CSS+variables. More references: `docs/obsidian-css-references.md`.
