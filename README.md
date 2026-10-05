# Synctax — a theme by [pxllbt](https://github.com/pxllbt)

[![Omarchy Theme](https://img.shields.io/badge/Omarchy%20Theme-4.x-blue?style=flat-square&labelColor=000000&color=1e66f5)](https://omarchy.org/themes)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square&labelColor=000000&color=1e66f5)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/pxllbt/synctax?style=flat-square&labelColor=000000&color=1e66f5)](https://github.com/pxllbt/synctax/stars)
[![GitHub Release](https://img.shields.io/github/v/release/pxllbt/synctax?style=flat-square&labelColor=000000&color=1e66f5)](https://github.com/pxllbt/synctax/releases)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green?style=flat-square&labelColor=000000&color=1e66f5)](https://github.com/pxllbt/synctax/pulls)

> **pxllbt's Synctax — a true-black Omarchy theme with one electric blue accent**

[Preview](#preview) · [Features](#features) · [Install](#install) · [Palette](#palette) · [Wallpapers](#wallpapers) · [License](#license)

A personal Omarchy theme built on a pitch-black foundation with a carefully
adapted pastel palette. `#000000` surfaces, near-white text, and a single
electric blue accent (`#1e66f5`) across the window border, selection, and
active elements. Eight semantic accent colors cover errors, warnings,
success, links, and more.

## Preview

![Synctax desktop preview](preview.png)

![Palette reference](palette-check.png)

## Features

- **True black base** — `#000000` with four surface depths
- **Single accent color** — electric blue (`#1e66f5`) on border, selection, and highlights
- **Readable on black** — four-step near-white text hierarchy
- **Hyprland-aligned** — active border uses the accent color
- **Three wallpapers** — cycle with `omarchy theme bg next`

## Install

```bash
omarchy theme install https://github.com/pxllbt/synctax
omarchy theme set synctax
```

Or use *Install > Style > Theme* in the Omarchy menu, then select **Synctax**
under *Style > Theme* (`Super + Ctrl + Shift + Space`).

Requires Omarchy 4 for semantic palette support.

## Palette

| Key | Color | Value | Role |
| --- | :---: | ----- | ---- |
| `background` | <span style="background:#000000;width:20px;height:20px;border-radius:3px;"></span> | `#000000` | pure black |
| `dark_background` | <span style="background:#090909;width:20px;height:20px;border-radius:3px;"></span> | `#090909` | surface |
| `darker_background` | <span style="background:#070707;width:20px;height:20px;border-radius:3px;"></span> | `#070707` | deep surface |
| `lighter_background` | <span style="background:#1a1a1a;width:20px;height:20px;border-radius:3px;"></span> | `#1a1a1a` | raised surface |
| `foreground` | <span style="background:#cdd6f4;width:20px;height:20px;border-radius:3px;"></span> | `#cdd6f4` | text |
| `dark_foreground` | <span style="background:#9ca0b0;width:20px;height:20px;border-radius:3px;"></span> | `#9ca0b0` | subtext |
| `light_foreground` | <span style="background:#bcc0cc;width:20px;height:20px;border-radius:3px;"></span> | `#bcc0cc` | text |
| `bright_foreground` | <span style="background:#e6e9f0;width:20px;height:20px;border-radius:3px;"></span> | `#e6e9f0` | headings |
| `accent` | <span style="background:#1e66f5;width:20px;height:20px;border-radius:3px;"></span> | `#1e66f5` | electric blue |
| `selection` | <span style="background:#1e66f5;width:20px;height:20px;border-radius:3px;"></span> | `#1e66f5` | selection |
| `muted` | <span style="background:#acb0be;width:20px;height:20px;border-radius:3px;"></span> | `#acb0be` | overlay |
| `red` | <span style="background:#d20f39;width:20px;height:20px;border-radius:3px;"></span> | `#d20f39` | coral — errors |
| `yellow` | <span style="background:#df8e1d;width:20px;height:20px;border-radius:3px;"></span> | `#df8e1d` | amber — warnings |
| `orange` | <span style="background:#d84e2b;width:20px;height:20px;border-radius:3px;"></span> | `#d84e2b` | peach |
| `green` | <span style="background:#40a02b;width:20px;height:20px;border-radius:3px;"></span> | `#40a02b` | emerald — success |
| `cyan` | <span style="background:#179299;width:20px;height:20px;border-radius:3px;"></span> | `#179299` | teal |
| `blue` | <span style="background:#1e66f5;width:20px;height:20px;border-radius:3px;"></span> | `#1e66f5` | electric — links |
| `magenta` | <span style="background:#ea76cb;width:20px;height:20px;border-radius:3px;"></span> | `#ea76cb` | pink |
| `brown` | <span style="background:#6c2715;width:20px;height:20px;border-radius:3px;"></span> | `#6c2715` | maroon |

## Wallpapers

Three backgrounds ship with the theme. Cycle them with `omarchy theme bg next`:

| File | Resolution | Description |
| --- | --- | --- |
| `backgrounds/gradient.jpg` | 5640×2400 | Dark blue gradient field, deep navy to light blue |
| `backgrounds/void.png` | 1920×1080 | Near-black background with subtle gray accents |
| `backgrounds/nebula.png` | 1920×1080 | Deep blue gradient with lighter blue highlights |

## License

MIT — see [LICENSE](LICENSE).

---

By [pxllbt](https://github.com/pxllbt). Part of the [Omarchy](https://omarchy.org) community themes.
