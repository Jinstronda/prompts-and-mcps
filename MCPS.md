# MCP Servers Configuration

`.mcp.json` (place in home directory `~/.mcp.json`)

```json
{
  "mcpServers": {
    "context7": {
      "command": "npx",
      "args": ["-y", "@upstash/context7-mcp"],
      "env": {
        "CONTEXT7_API_KEY": "YOUR_CONTEXT7_API_KEY"
      }
    },
    "playwright": {
      "command": "npx",
      "args": ["-y", "@playwright/mcp@latest"]
    },
    "chrome-devtools": {
      "command": "npx",
      "args": ["-y", "chrome-devtools-mcp@latest"]
    },
    "firecrawl": {
      "command": "npx",
      "args": ["-y", "firecrawl-mcp"],
      "env": {
        "FIRECRAWL_API_KEY": "YOUR_FIRECRAWL_API_KEY"
      }
    },
    "memory": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-memory"]
    },
    "sequential-thinking": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]
    },
    "magic": {
      "command": "npx",
      "args": ["-y", "@magicuidesign/mcp@latest"]
    },
    "neon": {
      "command": "npx",
      "args": ["-y", "@neondatabase/mcp-server-neon"],
      "env": {
        "NEON_API_KEY": "YOUR_NEON_API_KEY"
      }
    },
    "vercel": {
      "type": "http",
      "url": "https://mcp.vercel.com"
    },
    "cloudflare-docs": {
      "type": "http",
      "url": "https://docs.mcp.cloudflare.com/mcp"
    },
    "cloudflare-workers-builds": {
      "type": "http",
      "url": "https://builds.mcp.cloudflare.com/mcp"
    },
    "cloudflare-workers-bindings": {
      "type": "http",
      "url": "https://bindings.mcp.cloudflare.com/mcp"
    },
    "cloudflare-observability": {
      "type": "http",
      "url": "https://observability.mcp.cloudflare.com/mcp"
    },
    "clickhouse": {
      "type": "http",
      "url": "https://mcp.clickhouse.cloud/mcp"
    }
  }
}
```

# Enabled MCP Servers in Claude Code

In `settings.local.json` under `enabledMcpjsonServers`:
- context7
- playwright
- chrome-devtools
- firecrawl
- memory
- sequential-thinking
- magic
- neon
- vercel
- cloudflare-docs
- cloudflare-workers-builds
- cloudflare-workers-bindings
- cloudflare-observability
- clickhouse
