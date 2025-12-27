# NinjaEdit

A modern text editor for coders and sysadmins. Built with Python and Qt, designed for speed and daily use.

## Why Another Text Editor?

NinjaEdit fills the gap between heavyweight IDEs and bare-bones editors. It's for people who want:

- Syntax highlighting without the 500MB RAM footprint
- A command palette without VS Code's complexity
- Dark themes that actually look good
- An editor that starts instantly

## Features

### Editor
- **Syntax highlighting** - Python, JavaScript, TypeScript, HTML, CSS, JSON, SQL, Bash, PowerShell, Markdown
- **Line numbers** with current line highlight
- **Code minimap** for quick navigation
- **Split view** for side-by-side editing
- **Find/Replace** with regex support
- **Multi-file search** across all open tabs

### Productivity
- **Command palette** (Ctrl+Shift+P) - 70+ commands, fuzzy search
- **Symbol outline** - Jump to functions/classes
- **TODO aggregator** - Find all TODOs across open files
- **Quick transforms** - Base64, JSON format, hash, case conversion
- **Bookmarks** - Mark and jump between important lines

### Quality of Life
- **7 dark themes** - Ninja Dark, Midnight, Monokai Pro, Dracula, Nord, Tokyo Night, Synthwave
- **Session restore** - Remembers open files and positions
- **File watching** - Auto-reload when files change externally
- **Atomic saves** - Never corrupts files on crash
- **Single instance** - One window handles all file opens

## Quick Start

### Windows
```cmd
python run_ninjaedit.pyw
```
Or double-click `run_ninjaedit.pyw` (no console window)

### Linux
```bash
python3 run_ninjaedit.pyw
```

### Requirements
- Python 3.8+
- PySide6

```bash
pip install PySide6
```

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| Ctrl+Shift+P | Command palette |
| Ctrl+F | Find |
| Ctrl+H | Replace |
| Ctrl+G | Go to line |
| Ctrl+/ | Toggle comment |
| Ctrl+B | Toggle sidebar |
| Ctrl+M | Toggle minimap |
| Ctrl+\ | Split view |
| Alt+T | Quick transforms |

## Screenshots

| Editor | Command Palette | Themes |
|--------|-----------------|--------|
| Clean editing with syntax highlighting | Quick access to all commands | 7 hand-crafted dark themes |

## Configuration

Settings are stored in:
- Windows: `%APPDATA%/NinjaEdit/settings.json`
- Linux: `~/.ninjaedit/settings.json`

## Why Python/Qt?

- Cross-platform without Electron's bloat
- Native look and feel
- Fast enough for daily use
- Easy to extend and customize

## Author

**Takashi Kyoto** - [GitHub](https://github.com/TakashiKyoto) | [YouTube](https://youtube.com/@TakashiKyoto)

## License

MIT License - See [LICENSE](LICENSE) for details.
