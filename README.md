# Sync

An [Omarchy](https://omarchy.org/) theme: the **Catppuccin Latte** palette on a **vantablack** base.

![Sync palette](preview.png)

- Vantablack surfaces: `#000000` → `#1a1a1a`
- Catppuccin Latte chromatic accents: blue, red, peach, yellow, green, teal, mauve, pink
- Latte blue `#1e66f5` accent and window border
- Soft near-white text (`#cdd6f4`) — Latte's text family is designed for light backgrounds, so the
  foregrounds are lifted to stay readable on black while every accent keeps its exact Latte value

## Palette

| Role | Color |
| --- | --- |
| background | `#000000` |
| dark_background | `#090909` |
| darker_background | `#070707` |
| lighter_background | `#1a1a1a` |
| foreground | `#cdd6f4` |
| dark_foreground | `#9ca0b0` |
| light_foreground | `#bcc0cc` |
| bright_foreground | `#e6e9f0` |
| accent / blue / border | `#1e66f5` |
| red | `#d20f39` |
| yellow | `#df8e1d` |
| orange | `#d84e2b` |
| green | `#40a02b` |
| cyan | `#179299` |
| magenta | `#ea76cb` |
| brown | `#6c2715` |
| muted | `#acb0be` |

## Backgrounds

Three generated 4K wallpapers, cycled with `omarchy theme bg next`:

| File | Description |
| --- | --- |
| `backgrounds/ripple.png` | Concentric Latte blue / mauve / teal rings radiating on black |
| `backgrounds/horizon.png` | Faint Latte blue horizon line on black |
| `backgrounds/grid.png` | Dim blue dot grid on black |

## Install

```bash
omarchy theme install <this-repo-url>
omarchy theme set sync
```

Or manually: copy this directory to `~/.config/omarchy/themes/sync/` and run
`omarchy theme set sync`.

Terminals, Neovim, Helix, btop, GTK, the Omarchy shell and Hyprland borders are all generated
from `colors.toml` by Omarchy — nothing else to configure.

## License

[MIT](LICENSE) © 2026 pxllbt
