{
  "mcpServers": {
    "sequentialThinking": {
      "command": "npx",
      "args": [
        "-y",
        "@modelcontextprotocol/server-sequential-thinking"
      ]
    },
    "playwright": {
      "command": "npx",
      "args": [
        "-y",
        "@playwright/mcp@latest"
      ]
    },
    "context7": {
      "command": "npx",
      "args": [
        "-y",
        "@upstash/context7-mcp"
      ],
      "env": {}
    },
    "desktop-commander": {
      "command": "npx",
      "args": [
        "-y",
        "@wonderwhy-er/desktop-commander@latest"
      ],
      "env": {}
    },
    "github": {
      "url": "https://api.githubcopilot.com/mcp/",
      "headers": {
        "Authorization": "YOUR_GITHUB_TOKEN_HERE"
      }
    },
    "Neon": {
      "url": "https://mcp.neon.tech/mcp",
      "headers": {}
    },
    "chrome-devtools": {
      "command": "npx",
      "args": [
        "chrome-devtools-mcp@latest"
      ]
    }
  }
}