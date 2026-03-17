# ghostty-claude-shadcn

A Ghostty terminal theme based on [Claude's](https://claude.ai) official [shadcn UI](https://ui.shadcn.com) color palette.

![Dark Theme](screenshots/dark.png)
![Light Theme](screenshots/light.png)

## Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Orange | `#E67E22` | Cursor, primary accent |
| Teal | `#1B9AAA` | Links, cyan |
| Sage Green | `#88AB8E` | Success, green |
| Yellow | `#E5B945` | Warnings, yellow |
| Purple | `#B57EDC` | Magenta, purple |
| Navy | `#2C3E50` | Selection (dark mode) |
| Cream | `#F7F4EA` | Light background |
| Dark Gray | `#3A3A3A` | Dark background |

## Installation

### Option 1: Copy to Themes Directory

```bash
# macOS
cp claude-shadcn-dark claude-shadcn-light \
  ~/Library/Application\ Support/com.mitchellh.ghostty/themes/

# Linux
cp claude-shadcn-dark claude-shadcn-light \
  ~/.config/ghostty/themes/
```

### Option 2: Clone and Symlink

```bash
git clone https://github.com/YOUR_USERNAME/ghostty-claude-shadcn.git

# macOS
ln -s $(pwd)/ghostty-claude-shadcn/claude-shadcn-dark \
  ~/Library/Application\ Support/com.mitchellh.ghostty/themes/
ln -s $(pwd)/ghostty-claude-shadcn/claude-shadcn-light \
  ~/Library/Application\ Support/com.mitchellh.ghostty/themes/
```

## Usage

Add to your Ghostty config (`~/.config/ghostty/config` or macOS equivalent):

```
# Use dark theme
theme = claude-shadcn-dark

# Or light theme
theme = claude-shadcn-light
```

### Auto-Switch with System Appearance (macOS)

```
theme = light:claude-shadcn-light,dark:claude-shadcn-dark
```

## License

MIT License
