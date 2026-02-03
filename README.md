# BlackRoad VS Code Extension 💻

Deploy to BlackRoad directly from VS Code!

## Features

- **Deploy Command** - `BlackRoad: Deploy` command palette
- **Status Bar** - Deployment status in status bar
- **Notifications** - Toast notifications for deployments
- **API Testing** - Test API endpoints
- **Metrics View** - View analytics in sidebar

## Installation

### From Marketplace
```bash
code --install-extension blackroad.blackroad-vscode
```

### Manual
1. Download `.vsix` from releases
2. Extensions → Install from VSIX

## Usage

1. Open Command Palette (`Cmd+Shift+P` or `Ctrl+Shift+P`)
2. Type "BlackRoad"
3. Select command:
   - Deploy
   - View Metrics
   - Test API

## Configuration

Add to your `settings.json`:

```json
{
  "blackroad.apiKey": "your-api-key",
  "blackroad.autoRefresh": true
}
```

## Keyboard Shortcuts

- `Cmd+Shift+D` - Deploy
- `Cmd+Shift+M` - View Metrics

## Development

```bash
npm install
npm run compile
# Press F5 to debug
```

## License

MIT License

---

Part of the **BlackRoad Empire** 🚀
