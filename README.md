# Synctax — a theme by [pxllbt](https://github.com/pxllbt)

[![Omarchy Theme](https://img.shields.io/badge/Omarchy%20Theme-4.x-blue?style=flat-square&labelColor=000000&color=1e66f5)](https://omarchy.org/themes)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square&labelColor=000000&color=1e66f5)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/pxllbt/synctax?style=flat-square&labelColor=000000&color=1e66f5)](https://github.com/pxllbt/synctax/stars)
[![GitHub Release](https://img.shields.io/github/v/release/pxllbt/synctax?style=flat-square&labelColor=000000&color=1e66f5)](https://github.com/pxllbt/synctax/releases)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green?style=flat-square&labelColor=000000&color=1e66f5)](https://github.com/pxllbt/synctax/pulls)

> **Pure black · Electric blue · 4K wallpapers · Hyprland & Wayland**

[Preview](#preview) • [Install](#install) • [Palette](#palette) • [Wallpapers](#backgrounds) • [License](#license)

**Total black. One electric blue. Everything in sync.**

A true-black Omarchy theme: pure `#000000` surfaces, near-white text,
and a single electric blue accent (`#1e66f5`) that runs through the
window border, selection, and every active element — so the whole
desktop agrees with itself. Eight accent colors cover the semantic
roles: errors, warnings, success, links, and more.

## Preview

![Synctax desktop preview](preview.png)

![Palette reference](palette-check.png)

## Why Synctax

- **Pure black base** — `#000000` with four surface depths (`#070707` → `#1a1a1a`)
- **One accent everywhere** — border, selection, and highlights all sit on `#1e66f5`
- **Readable on black** — four-step near-white text family
- **Hyprland-matched** — active border uses the accent (`rgba(1e66f5ee)`)
- **Wallpapers included** — three generated 4K backgrounds

## Install

```bash
omarchy theme install https://github.com/pxllbt/synctax
omarchy theme set synctax
```

Or use *Install > Style > Theme* in the Omarchy menu, then pick **Synctax**
under *Style > Theme* (`Super + Ctrl + Shift + Space`).

Requires Omarchy 4 — the palette uses the semantic key set.

## Palette

| Key | Value | Role |
| --- | ----- | ---- |
| `background` | `#000000` | pure black |
| `dark_background` | `#090909` | surface |
| `darker_background` | `#070707` | deep surface |
| `lighter_background` | `#1a1a1a` | raised surface |
| `foreground` | `#cdd6f4` | text |
| `dark_foreground` | `#9ca0b0` | subtext |
| `light_foreground` | `#bcc0cc` | text |
| `bright_foreground` | `#e6e9f0` | headings |
| `accent` | `#1e66f5` | electric blue |
| `selection` | `#1e66f5` | selection |
| `muted` | `#acb0be` | overlay |
| `red` | `#d20f39` | coral — errors |
| `yellow` | `#df8e1d` | amber — warnings |
| `orange` | `#d84e2b` | peach |
| `green` | `#40a02b` | emerald — success |
| `cyan` | `#179299` | teal |
| `blue` | `#1e66f5` | electric — links |
| `magenta` | `#ea76cb` | pink |
| `brown` | `#6c2715` | maroon |

## Background

Three generated 4K wallpapers ship with the theme; cycle them with
`omarchy theme bg next`:

| File | Description |
| --- | --- |
| `backgrounds/ripple.png` | Concentric blue / mauve / teal rings radiating on black |
| `backgrounds/horizon.png` | A soft blue horizon glow on black |
| `backgrounds/grid.png` | A dim blue dot grid on black |

## License

MIT — see [LICENSE](LICENSE).

---

Made with <3 by [pxllbt](https://github.com/pxllbt). Part of the [Omarchy](https://omarchy.org) community themes.
