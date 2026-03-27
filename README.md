# stitts-plugins

Custom Claude Code plugins by stitts-dev. For official Anthropic and third-party plugins, use the [official marketplace](https://github.com/anthropics/claude-plugins-official).

## Plugins

- **mcp-tts** - ElevenLabs TTS for Claude Code. Gives Claude a voice via the `speak` tool.

## Installation

```
/plugin install mcp-tts@stitts-plugins
```

## Adding a new plugin

1. Create a directory under `external_plugins/`
2. Add `.claude-plugin/plugin.json` and optionally `.mcp.json`
3. Register it in `.claude-plugin/marketplace.json`
