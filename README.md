# Code Agent Switch (`cas`)

Lightweight provider switcher for Claude Code, Codex, and OpenCode.

- Overlay model: only switch `base_url` / API key (and a few related fields), not whole configs
- Local proxy for hot-switching
- MCP enable/disable
- TUI (Textual) + optional macOS menu bar later

```bash
cas          # TUI
cas use <id> # quick switch
```
