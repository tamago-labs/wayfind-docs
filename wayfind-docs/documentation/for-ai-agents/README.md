# For AI Agents

Wayfind provides infrastructure for AI agents beyond Grok Bot. Use agent skills, MCP servers, and multi-agent coordination to bring Wayfind capabilities to your preferred agent.

## Integration Options

| Agent | Integration Method | Status |
|-------|-------------------|--------|
| **[Grok Bot](https://x.ai/grok-bot)** | One-click template import with built-in skills | Primary (Recommended) |
| **[Meta Muse](https://x.ai/)** | MCP Server / Agent Skills | Supported |
| **[OpenAI Dots](https://openai.com/)** | MCP Server / Agent Skills | Supported |
| **[Claude Duet](https://www.anthropic.com/)** | MCP Server / Agent Skills | Supported |
| **[Cursor](https://www.cursor.com/)** | MCP Server | Supported |
| **[Cherry Studio](https://github.com/AIDC-AI/CherryStudio)** | MCP Server | Supported |

## Core Components

### Agent Skills
Pre-defined skill sets for each template that give agents context, workflows, and best practices. Skills are installed per-template from their respective GitHub repos.

### MCP Servers
Model Context Protocol servers expose Wayfind tools to any MCP-compatible agent. Each template has its own MCP server with specialized tools.

### Agentic Wallet
Agents get their own encrypted wallets to sign and send transactions autonomously, with approval workflows for security.

### Multi-Agent Coordination
Enable teams of specialized bots to work together - CFO, HR, Research, Marketing, etc. - sharing context and coordinating complex workflows.

## Getting Started

1. **For Grok Bot:** [Import a template](../getting-started/grok-bot-setup.md) - easiest path
2. **For other agents:** [Set up MCP](mcp-servers.md) - configure for your agent

## Documentation

- [Agent Skills](agent-skills.md) - Installing and using skills
- [MCP Servers](mcp-servers.md) - Available servers and configuration
- [Agentic Wallet](agentic-wallet.md) - Wallet management
- [Multi-Agent Coordination](multi-agent-coordination.md) - Building bot teams
- [Available Tools by Template](tools-by-template.md) - Tool reference
