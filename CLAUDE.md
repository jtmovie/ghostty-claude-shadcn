# CLAUDE.md - ghostty-claude-shadcn

Ghostty terminal theme based on Claude's official shadcn UI color palette.

## Overview

A Ghostty terminal theme that brings Claude's beautiful shadcn UI colors to your terminal. Features automatic light/dark mode support.

## Structure

```
ghostty-claude-shadcn/
├── claude-shadcn-light    # Light theme
├── claude-shadcn-dark     # Dark theme
└── CLAUDE.md
```

## Installation

1. Copy both theme files to your Ghostty themes directory:
   ```bash
   mkdir -p ~/.config/ghostty/themes
   cp *.shadcn-* ~/.config/ghostty/themes/
   ```

2. Add to your Ghostty config (`~/.config/ghostty/config`):
   ```bash
   theme = light:claude-shadcn-light,dark:claude-shadcn-dark
   ```

3. Restart Ghostty to apply the theme.

## Color Palette

Based on Claude's official shadcn UI design system, optimized for terminal readability.

### Dark Theme
- Background: `#83827d`
- Foreground: `#D4CFC4`
- Cursor: `#E67E22`
- Selection: `#2C3E50`

### Light Theme
- Background: `#e9e6dc`
- Foreground: `#4A4A4A`
- Cursor: `#E67E22`
- Selection: `#E67E22`

## License

MIT
