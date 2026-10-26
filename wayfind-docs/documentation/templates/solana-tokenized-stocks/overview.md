# Solana Tokenized Stocks - Overview

The Solana Tokenized Stocks template equips your Grok Bot with market data, risk intelligence, and trading tools to manage tokenized equity portfolios on Solana and across EVM chains.

## What Are Tokenized Stocks?

Tokenized equities represent shares of real companies onchain. One company like Tesla can have multiple onchain representations (e.g., TSLAx, TSLAon, rTSLA) with different prices, liquidity, and issuers. The template helps your bot understand and navigate these different versions.

## Key Features

- **Multi-Representation Resolution** - Identifies and compares different onchain versions of the same stock
- **Real-time Market Data** - Access to prices, market cap, volume, liquidity across issuers
- **Portfolio Tracking** - Monitor real wallet holdings or create simulated portfolios
- **AI Risk Analysis** - Personalized risk assessment based on holdings and risk profile
- **OKX DEX Trading** - Execute swaps through OKX DEX Router
- **Multi-Chain Support** - Works across Solana, Ethereum, Arbitrum, and BNB Chain

## Components

This template uses the following Wayfind components:
- **Wayfind Platform** - Data backbone for market data, risk analysis, portfolio tracking
- **MCP Server** (`@tamago-labs/wayfind-mcp`) - Tools for wallet balances, swaps, token data, risk profiles
- **Agent Skills** - Grok Bot plugin for intent routing and workflows

## Getting Started

1. [Import the template](https://x.ai/bot/EpQzEq9pQvX_utfgsxzbj) to Grok Bot
2. Get your API key from [wayfind.click](https://wayfind.click/) dashboard (optional for some data)
3. Let your bot guide you through setup
4. Start exploring tokenized stocks or analyzing your portfolio
