claude-saka mcp add --scope project playwright -- npx @playwright/mcp@latest

https://playwright.dev/mcp/clients/vscode

REPO_ROOT/.mcp.json

{
  "mcpServers": {
    "playwright": {
      "command": "npx",
      "args": ["@playwright/mcp@latest"]
    }
  }
}