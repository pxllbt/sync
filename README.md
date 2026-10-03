# Sync

![Omarchy](https://img.shields.io/badge/Omarchy-4.x-1e66f5?style=flat-square)
![Catppuccin](https://img.shields.io/badge/Catppuccin-Latte-1e66f5?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-1e66f5?style=flat-square)

The [Catppuccin Latte](https://github.com/catppuccin/catppuccin) palette,
synced onto a vantablack base.

Every Latte accent keeps its exact value — blue, red, peach, yellow, green,
teal, pink, maroon — while the surfaces drop to pure black (`#000000`) and
the text family lifts to near-white so it stays readable. The accent, the
window border and the selection all sit on Latte blue `#1e66f5`, so the
whole desktop agrees with itself.

![The desktop](preview.png)

*Mock-up, not a screenshot — every element is rendered from the palette.*

![Palette](palette-check.png)

## Install

```bash
omarchy theme install https://github.com/pxllbt/sync
omarchy theme set sync
```

Or use *Install > Style > Theme* in the Omarchy menu, then pick **Sync**
under *Style > Theme* (`Super + Ctrl + Shift + Space`).

Requires Omarchy 4 — the palette uses the semantic key set.

## Palette

| Key | Value | |
|-----|-------|---|
| `background` | `#000000` | vantablack |
| `dark_background` | `#090909` | |
| `darker_background` | `#070707` | |
| `lighter_background` | `#1a1a1a` | |
| `foreground` | `#cdd6f4` | text |
| `dark_foreground` | `#9ca0b0` | subtext |
| `light_foreground` | `#bcc0cc` | |
| `bright_foreground` | `#e6e9f0` | |
| `accent` | `#1e66f5` | Latte blue |
| `selection` | `#1e66f5` | |
| `muted` | `#acb0be` | overlay |
| `red` | `#d20f39` | Latte red |
| `yellow` | `#df8e1d` | Latte yellow |
| `orange` | `#d84e2b` | Latte peach |
| `green` | `#40a02b` | Latte green |
| `cyan` | `#179299` | Latte teal |
| `blue` | `#1e66f5` | Latte blue |
| `magenta` | `#ea76cb` | Latte pink |
| `brown` | `#6c2715` | Latte maroon |

## Backgrounds

Three generated 4K wallpapers ship with the theme; cycle them with
`omarchy theme bg next`:

| File | Description |
| --- | --- |
| `backgrounds/ripple.png` | Concentric Latte blue / mauve / teal rings radiating on black |
| `backgrounds/horizon.png` | A soft Latte blue horizon glow on black |
| `backgrounds/grid.png` | A dim blue dot grid on black |

## License

[MIT](LICENSE) © 2026 pxllbt
