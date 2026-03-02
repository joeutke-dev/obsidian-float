# Float on Top — Obsidian Plugin

Keep Obsidian floating above all other windows, with adjustable translucency.

## Features

- **Always on top toggle** — via ribbon icon or command
- **Translucency** — opacity presets + fine-grained slider (50–100%)
- **Persistent state** — remembers your settings between sessions
- **Hotkey support** — assign keyboard shortcuts to toggle commands

## Installation

2. Copy `main.js`, `manifest.json`, and `styles.css` to:
   ```
   <your-vault>/.obsidian/plugins/float-on-top/
   ```
3. In Obsidian → Settings → Community Plugins → enable **Float on Top**

## Usage

| Action | How |
|---|---|
| Toggle always-on-top | Click the pin icon in the ribbon |
| Adjust opacity | Settings → Float on Top → drag slider or pick preset |
| Cycle presets | Command palette: "Cycle opacity preset" |

## Opacity Presets

| Preset | Value |
|---|---|
| Opaque | 100% |
| Barely there | 95% |
| Light | 90% |
| Medium | 80% |
| Heavy | 70% |

## Notes

- Desktop only (macOS, Windows, Linux) — uses Electron window APIs
- Opacity affects the entire Obsidian window. Values above 85% are recommended for readability.
- Always-on-top and opacity are reset to defaults when the plugin is disabled.
