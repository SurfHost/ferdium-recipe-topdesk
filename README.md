# Ferdium Recipe: TOPdesk

A [Ferdium](https://ferdium.org) recipe for [TOPdesk](https://www.topdesk.com) IT Service Management.

## Installation (Dev Recipe)

1. Copy the recipe files to your Ferdium dev recipes folder:
   - **Windows:** `%APPDATA%\Ferdium\recipes\dev\topdesk\`
   - **Linux:** `~/.config/Ferdium/recipes/dev/topdesk/`
   - **macOS:** `~/Library/Application Support/Ferdium/recipes/dev/topdesk/`
2. Restart Ferdium
3. Add TOPdesk as a new service
4. Enter your TOPdesk subdomain (e.g. `company` for `https://company.topdesk.net`)

## Files

- `package.json` — Recipe configuration
- `index.js` — Main recipe entry point
- `webview.js` — Webview injection script
- `icon.svg` — TOPdesk logo

## License

MIT
