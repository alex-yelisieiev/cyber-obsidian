# Cyber

![Cyber theme preview](screenshot.png)

An [Obsidian](https://obsidian.md) theme inspired by the [Cyberpunk](https://www.cyberpunk.net) brand system — Night City void chrome, clipped HUD geometry, and California-yellow daylight surfaces.

Supports **dark** (Night City) and **light** (California yellow) modes.

## Features

- Pure-black Night City chrome across the full app shell and editor
- Warm cream California light mode for readable long-form notes (not a blinding yellow page)
- Cyber yellow (`#FCEE0A`) primary accent, cyan HUD focus (`#00F0FF`), hot signal red danger
- Notched / clipped corners — hard borders, ghost outline buttons, solid yellow CTAs
- Sharp rectangular tags and yellow-fill checkboxes
- Distinct Night City callout treatments per type with filled icon chips
- Print styles use solid fills only (no gradient banding in PDF)
- Optional Style Settings toggles (`cyber-wide`, `cyber-hud-labels`)

## Installation

### Community themes (recommended)

Once published to the Obsidian community directory:

1. Open **Settings → Appearance**
2. Click **Manage** next to Themes
3. Search for **Cyber**
4. Click **Install**, then **Use**

### Manual install

1. Download or clone this repository
2. Copy the theme folder into your vault at `.obsidian/themes/Cyber/`
3. Open **Settings → Appearance → Themes**
4. Select **Cyber**

### Requirements

- Obsidian `1.5.0` or newer

## Modes

| Mode | Look |
| --- | --- |
| Dark (Night City) | Unified pure-black / near-black chrome + editor, yellow accent, cyan focus |
| Light (California yellow) | Warm cream / pale-yellow paper (`#F7F4D8` / `#FFFEF0`), black text, yellow accents |

Toggle under **Settings → Appearance → Base color scheme**.

## Fonts

Interface and headings use **[Rajdhani](https://github.com/itfoundry/rajdhani)** (SIL OFL 1.1) as a technical / futuristic stand-in for the proprietary Refinery-25 + BlenderPro faces used on cyberpunk.net. Rajdhani is embedded locally in `theme.css` — the theme never loads remote fonts.

Monospace stack: JetBrains Mono → SF Mono → ui-monospace → Menlo.

Font license: [SIL OFL 1.1](OFL-Rajdhani.txt).

## License

Theme code and styles are released under the [MIT License](LICENSE).  
Rajdhani is licensed under the [SIL Open Font License 1.1](OFL-Rajdhani.txt).
