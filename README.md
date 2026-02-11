# My Claude Code Setup

Full config for Claude Code. Prompt, MCPs, settings, plugins.

## Files

| File | What it is | Where it goes |
|------|-----------|---------------|
| `prompt-2026-02-11.md` | Main system prompt (CLAUDE.md) | `~/CLAUDE.md` |
| `MCPS.md` | MCP server configs (keys redacted) | `~/.mcp.json` |
| `claude-code-settings.json` | Global settings + plugins | `~/.claude/settings.json` |
| `claude-code-settings-local.json` | Local settings + enabled MCPs | `~/.claude/settings.local.json` |

## Quick Setup

1. Copy `prompt-2026-02-11.md` to `~/CLAUDE.md`
2. Copy the JSON from `MCPS.md` to `~/.mcp.json` and fill in your API keys
3. Copy `claude-code-settings.json` to `~/.claude/settings.json`
4. Copy `claude-code-settings-local.json` to `~/.claude/settings.local.json`

## Plugins Enabled

- frontend-design (both claude-code-plugins and claude-plugins-official)
- explanatory-output-style
- security-guidance
- document-skills
- code-simplifier
- pr-review-toolkit
- commit-commands
- feature-dev
- learning-output-style
- agent-sdk-dev
- ralph-loop
- pyright-lsp

## MCP Servers

**Local (npx):** context7, playwright, chrome-devtools, firecrawl, memory, sequential-thinking, magic, neon

**HTTP:** vercel, cloudflare-docs, cloudflare-workers-builds, cloudflare-workers-bindings, cloudflare-observability, clickhouse
