# Warp Theme Guidelines

## Theme Format
- Use YAML/YML format with `.yaml` or `.yml` extension
- Required keys: `accent`, `background`, `foreground`, `details`, `terminal_colors`
- Terminal colors must include both `normal` and `bright` color sets
- Include comments for color names/references (e.g., `# gruvbox dark0_hard`)

## Naming Conventions
- Theme filename format: `username_theme-name.yaml`
- Use lowercase with hyphens for multi-word theme names

## Color Guidelines
- Use hex color codes (e.g., `#fe8019`)
- Ensure good contrast between background and foreground colors
- For `details` key, use either `darker` or `lighter`

## Development
- Test themes by selecting them in Warp's appearance settings
- No formal linting or testing commands required
- Visual inspection is the primary validation method