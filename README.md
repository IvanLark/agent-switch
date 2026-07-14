# Agent Switch (`asw`)

Lightweight provider switcher for Claude Code, Codex, and OpenCode.

- Overlay model: only switch `base_url` / API key (and a few related fields), not whole configs
- Local proxy for hot-switching
- MCP enable/disable
- macOS-native app later; optional TUI / menu bar

```bash
asw          # app / TUI entry
asw use <id> # quick switch
```

## Design notes

- [CC Switch research](docs/cc-switch-research-by-codex.md): provider snapshots, switch modes, proxy takeover, MCP — and design constraints for Agent Switch.
