# Voidpad

A blank page for writing. Open it, type, and everything is saved in your browser — nothing leaves your device.

**[Open Voidpad](https://abhushansahu.github.io/voidpad/)**

## Features

- **Instant** — single HTML file, no dependencies, loads fast even on slow connections
- **Blank canvas** — centered typography, system-aware light/dark theme, no clutter
- **Auto-save** — every keystroke saved to `localStorage`; close the tab and come back anytime
- **Markdown preview** — write in markdown, toggle preview when you want to see the result
- **Multiple pages** — work on several documents, switch between them from the side rail
- **Print-ready** — `Ctrl/Cmd+P` prints a clean A4 page with rendered markdown
- **Private** — no server, no accounts, no tracking

## Keyboard shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd+E` | Toggle preview / edit |
| `Ctrl/Cmd+P` | Print |
| `Ctrl/Cmd+N` | New page |
| `Ctrl/Cmd+Shift+]` | Next page |
| `Ctrl/Cmd+Shift+[` | Previous page |
| `Ctrl/Cmd+L` | Cycle theme (system → light → dark) |

Click the dot in the bottom-left corner to cycle themes too.

## How it works

Voidpad is one self-contained HTML file. All your pages and preferences live in your browser's `localStorage` under the key `voidpad-state`. Clearing site data will remove your content.

## License

MIT
