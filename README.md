# PMP - Personal Memory Protocol

A local-first personal memory system that helps you capture, organize, and recall information instantly.

## Download

Download the latest version from the [Releases](https://github.com/Jaghadish/pmp/releases) page.

### Windows
- **PMP_1.0.0_x64-setup.exe** - Installer (recommended)
- **PMP_1.0.0_x64_en-US.msi** - MSI installer
- **pmp-daemon.exe** - Standalone MCP daemon for Claude Desktop

## Features

- **Instant Capture** - Global hotkey (Ctrl+Shift+M) to save anything quickly
- **Smart Categories** - Organize memories into customizable categories
- **Local-First** - All data stored locally for privacy
- **MCP Integration** - Works with Claude Desktop
- **REST API** - Integrate with other apps
- **Fast Search** - Find memories instantly

## Claude Desktop Integration

Add to your Claude Desktop config:

```json
{
  "mcpServers": {
    "pmp": {
      "command": "C:/path/to/pmp-daemon.exe",
      "args": ["--mcp"]
    }
  }
}
```

## License

Apache License 2.0

Copyright 2024 Jaghadish
