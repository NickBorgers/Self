# Claude Code Notes

## Testing

### Playwright
- This devcontainer environment does not have a display server (X11)
- When using Playwright, always use `headless: true` mode
- Example: `chromium.launch({ headless: true })`

### Jekyll Development Server
- Jekyll runs with auto-regeneration enabled
- File changes are automatically detected and rebuilt without restarting the server
- No need to wait for manual rebuilds after editing markdown or HTML files
