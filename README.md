# DIDADI

![DIDADI preview](screenshot.png)

DIDADI is a fixed Obsidian app theme prepared for Tommy's DIDADI vault style.

The theme is packaged as an independent app theme. It works without Yue, without the Style Settings plugin, and without CSS snippets. All heading levels, from H1 through H6, use the same DIDADI heading color by default.

## Features

- Fixed DIDADI heading color for H1, H2, H3, H4, H5, and H6.
- Orange accent defaults aligned with the vault appearance.
- Light and dark mode support using Obsidian CSS variables.
- No remote assets, no external fonts, no Style Settings metadata, and no dependency on another theme.

## Install Manually

1. Copy this repository folder to `.obsidian/themes/DIDADI` in an Obsidian vault.
2. In Obsidian, open Settings, then Appearance.
3. Select `DIDADI` from the theme dropdown.

## Community Directory Notes

The display name is `DIDADI`. The GitHub repository may be named `DIDADI-theme`, but the theme name itself should not contain the word `Theme` because Obsidian Community directory names disallow it for themes.

This theme is an independent CSS variables theme. Yue and Style Settings were used only as a visual reference while identifying the desired vault appearance; their CSS is not included.

## Release Checklist

- `manifest.json` version uses `x.y.z`.
- GitHub release tag matches the `manifest.json` version.
- Release assets include `manifest.json` and `theme.css`.
- Repository root includes `README.md`, `LICENSE`, `manifest.json`, `theme.css`, and a 512 x 288 screenshot.
- No remote assets, telemetry, dynamic ads, or updater mechanism.

## License

MIT. See `LICENSE` for details.
