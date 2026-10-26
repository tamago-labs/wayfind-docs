# Using with Other AI Agents (MCP)

Use Wayfind MCP servers with AI agents like Cursor, Cherry Studio, Claude Code, or any MCP-compatible client to access Wayfind tools.

## Overview

Each template has its own MCP server with specialized tools for that use case. You can install them globally via npm or run with npx.

## Available MCP Servers

| Template | Package | Repository |
|----------|---------|-------------|
| Solana Tokenized Stocks | `@tamago-labs/wayfind-mcp` | [wayfind-mcp](https://github.com/tamago-labs/wayfind-mcp) |
| Circle USDC Payments (Arc) | `@tamago-labs/wayfind-arc-mcp` | [wayfind-arc](https://github.com/tamago-labs/wayfind-arc) |
| Mezo Bitcoin Finance | `@tamago-labs/wayfind-mezo` | [wayfind-mezo](https://github.com/tamago-labs/wayfind-mezo) |

## Setup

### 1. Get API Key
Get your API key from [wayfind.click](https://wayfind.click/) dashboard.

### 2. Configure Your Agent
Add the MCP server to your agent's configuration. Example config:

```json
{
  "mcpServers": {
    "wayfind-solana": {
      "command": "npx",
      "args": ["-y", "@tamago-labs/wayfind-mcp"],
      "env": { "WAYFIND_API_KEY": "your_key_here" }
    }
  }
}
```

Replace the package name and server key based on which template you're using.

### 3. Install and Run
For most agents, adding to config and restarting is enough. You can also install globally:

```bash
npm install -g @tamago-labs/wayfind-mcp
```

## Usage

Once configured, your agent can use Wayfind tools to:
- Check wallet balances and token holdings
- Get tokenized stock data and quotes
- Execute swaps via OKX DEX (Solana template)
- Manage USDC across chains (Arc template)
- Interact with Mezo protocols (Mezo template)
- Access risk profiles and portfolio data

## Notes

- API key is optional when accessing Solana Tokenized Stocks data
- API key may be required for other MCP tools depending on the template
- For Grok Bot, use the [one-click template import](grok-bot-setup.md) instead - it's easier
- Each MCP server is tailored to its template's capabilities
