{
  "mcpServers": {
    "supabase": {
      "command": "npx",
      "args": [
        "@supabase/mcp-server-supabase@latest",
        "--access-token",
        "YOUR_SUPABASE_ACCESS_TOKEN"
      ]
    },
    "puppeteer": {
      "command": "npx",
      "args": ["@modelcontextprotocol/server-puppeteer@latest"]
    },
    "sequentialThinking": {
      "command": "npx",
      "args": ["@modelcontextprotocol/server-sequential-thinking@latest"]
    },
    "context7": {
      "command": "npx",
      "args": ["@upstash/context7-mcp@latest"]
    },
    "desktop-commander": {
      "command": "npx",
      "args": ["@wonderwhy-er/desktop-commander@latest"]
    },
    "playwright": {
      "command": "npx",
      "args": ["@playwright/mcp@latest"]
    },
    "svelte": {
      "command": "npx",
      "args": ["-y", "@sveltejs/mcp@latest"]
    },
    "figma": {
      "url": "https://mcp.figma.com/mcp"
    },
    "figma-desktop": {
      "url": "http://127.0.0.1:3845/mcp"
    },

    "github": {
      "type": "http",
      "url": "https://api.githubcopilot.com/mcp/",
      "headers": {
        "Authorization": "Bearer YOUR_GITHUB_PERSONAL_ACCESS_TOKEN"
      }
    }
  }
}
