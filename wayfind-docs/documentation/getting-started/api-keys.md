# API Keys

Get and manage your Wayfind API key from the dashboard.

## Getting Your API Key

1. Go to [wayfind.click](https://wayfind.click/) dashboard
2. Connect your wallet - either Solana or EVM
3. Once connected, your API key will be ready to copy from the dashboard
4. Use it in your MCP configuration or provide it to your bot when prompted

## Using Your API Key

For MCP servers, add it to your configuration:

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

## AI Credits

You can request AI credits (free for now) from the dashboard to access AI-powered features like portfolio risk assessment.

- **Free credits** available for new users
- Used for AI Risk Review and Chat Further features
- Credits are consumed based on token usage
- Manage and request credits from the dashboard when connected with your wallet

## Notes

- API key is optional when accessing Solana Tokenized Stocks data via MCP
- Keep your API key secure - don't share it publicly
- API key is linked to your connected wallet
