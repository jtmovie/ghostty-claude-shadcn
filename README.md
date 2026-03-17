# ghostty-claude-shadcn

Ghostty terminal theme based on Claude's official shadcn UI color palette.

## Overview

A Ghostty terminal theme that brings Claude's beautiful shadcn UI colors to your terminal. Features automatic light/dark mode support.

## Installation

1. Copy both theme files to your Ghostty themes directory:
   ```bash
   mkdir -p ~/.config/ghostty/themes
   cp claude-shadcn-* ~/.config/ghostty/themes/
   ```

2. Add to your Ghostty config (`~/.config/ghostty/config`):
   ```bash
   theme = light:claude-shadcn-light,dark:claude-shadcn-dark
   ```

3. Restart Ghostty to apply the theme.

## Color Palette

### Dark Theme
- Background: `#3A3A3A`
- Foreground: `#D4CFC4`
- Cursor: `#E67E22`
- Selection: `#2C3E50`

### Light Theme
- Background: `#FAFAFA`
- Foreground: `#4A4A4A`
- Cursor: `#E67E22`
- Selection: `#E67E22`

## License

MIT
