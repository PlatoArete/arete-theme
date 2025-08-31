# Arete Theme

A custom VS Code theme with warm, vibrant colors and excellent contrast for better code readability.

## Features

- **Dark theme** with consistent `#110f10` background across editor, sidebar, and panels
- **Warm color palette** optimized for syntax distinction and eye comfort
- **Enhanced UI elements** with darker tones (`#0f0d0e`) for tab bar, activity bar, and title bar
- **SAS language support** with dedicated syntax highlighting
- **Gold accents** (`#d4af37`) for active elements and highlights

## Color Scheme

- **Keywords/Storage**: `#ffcc02` (warm gold, bold)
- **Variables**: `#ff6b6b` (coral/salmon)
- **Strings**: `#00bfff` (neon blue)
- **Functions/Entities**: `#00d2d3` (bright cyan/turquoise)
- **Support/Properties**: `#ffa502` (orange)
- **Constants**: `#8cc8ff` (light blue)
- **Comments**: `#9d7cd8` (muted purple, italic)

## Installation

### From VSIX (Recommended)
1. Download the latest `arete-theme-X.X.X.vsix` file
2. Install via command line:
   ```bash
   code --install-extension arete-theme-0.0.5.vsix
   ```
3. Activate the theme:
   - Open VS Code
   - Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
   - Type "Preferences: Color Theme"
   - Select "Arete Theme"

### From Source
1. Clone this repository
2. Package the theme:
   ```bash
   npm install -g @vscode/vsce
   vsce package
   ```
3. Install the generated VSIX file

## SAS Language Support

This theme includes enhanced syntax highlighting for SAS files. Works best with the [SAS extension](https://github.com/hui-ts/vscode-sas).

## Development

The theme is defined in `themes/arete-theme.json`. After making changes:
1. Run `vsce package` to create a new VSIX
2. Install with `code --install-extension arete-theme-X.X.X.vsix`
3. Reload VS Code to see changes

## License

This theme is based on the Doki Theme: TypeMoon: Ishtar but has been extensively modified with custom colors and UI improvements.