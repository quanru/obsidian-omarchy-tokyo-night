# Omarchy Tokyo Night

An Obsidian theme inspired by Omarchy's Tokyo Night palette, with a light mode based on the community Tokyo Day palette. It keeps Obsidian's native layout and font settings and works offline without plugins or extra fonts.

## Install

In Obsidian, open **Settings → Appearance → Themes → Manage**, search for **Omarchy Tokyo Night**, and select **Install and use**. For manual installation, download a release and copy `manifest.json` and `theme.css` into `.obsidian/themes/Omarchy Tokyo Night/` in your vault. Then select the theme in **Settings → Appearance**.

## Use and customize

Choose **Light**, **Dark**, or **Adapt to system** under **Settings → Appearance → Base color**. Dark mode uses Tokyo Night; light mode uses Tokyo Day. This theme has no Style Settings options. Obsidian's built-in font settings remain available. Other CSS snippets, plugin styles, and custom accent colors may change the result.

On desktop, darker side panels, a thin active-pane frame, numbered pane tabs, square file highlights, crisp section rules, and matching search surfaces echo Omarchy's tiled workspace. The pane number follows focus; the quick switcher, command palette, sidebar search, and settings window share a sharp focus treatment without changing your note layout or fonts.

Canvas nodes, graph controls, and community theme dialogs use the same square panels and accent edges. On mobile, the file drawer, search prompt, new-tab actions, and bottom navigation carry that treatment while keeping Obsidian's touch layout.

## Preview

![Tokyo Night dark mode](images/dark.png)

![Tokyo Day light mode](images/light.png)

The theme also styles Canvas, the community theme browser, and mobile navigation. See the [dark Canvas](images/canvas-dark.png), [light Canvas](images/canvas-light.png), [theme browser](images/theme-browser-dark.png), [dark mobile note](images/mobile-dark.png), [light mobile note](images/mobile-light.png), and [mobile file search](images/mobile-search-dark.png).

## Palette

| Role       | Tokyo Night (dark)              | Tokyo Day (light) |
| ---------- | ------------------------------- | ----------------- |
| Background | `#1a1b26`                       | `#e1e2e7`         |
| Text       | `#a9b1d6`                       | `#3760bf`         |
| Accent     | `#7aa2f7`                       | `#2e7de9`         |
| Selection  | Omarchy Tokyo Night `selection` | `#b7c1e3`         |

Dark-mode heading colors follow Omarchy's Obsidian template. Secondary text and code comments are slightly brighter for readability at small sizes. The theme is an independent Obsidian adaptation; it is not an official Omarchy release and does not reproduce Linux window borders or wallpapers.

## Sources and license

- [Omarchy Tokyo Night palette](https://github.com/omacom/omarchy/blob/quattro/themes/tokyo-night/colors.toml)
- [Community Tokyo Day palette by Kayle Gishen](https://github.com/kayleg/omarchy-tokyo-day/blob/main/colors.toml)
- [Tokyo Night Day upstream by Folke Lemaitre](https://github.com/folke/tokyonight.nvim)
- [Omarchy Obsidian template](https://github.com/omacom/omarchy/blob/quattro/default/themed/obsidian.css.tpl)

Sources checked on September 26, 2026. Licensed under MIT; see [LICENSE](LICENSE).

## Verification

Tested in an isolated vault with Obsidian 1.14.2 on macOS, covering theme loading, colors, reading and live-preview modes, text input, settings, Canvas, graph controls, the community theme browser, and switching between light and dark. Also tested in an isolated vault with Obsidian 1.12.4 on an Android emulator, covering the file drawer, file search, notes, new-tab actions, and bottom navigation in both modes. iOS and third-party plugins have not yet been verified.
