# Templates Overview

Wayfind provides three purpose-built templates for Grok Bot, each equipped with specialized agent skills, MCP tools, and workflows for specific onchain use cases.

## Available Templates

### 1. Solana Tokenized Stocks
**[Import Template](https://x.ai/bot/EpQzEq9pQvX_utfgsxzbj)** | [Learn More](../templates/solana-tokenized-stocks/README.md)

Gives your bot market context, risk awareness, and trading rails to manage tokenized stock portfolios on Solana. Resolves multiple onchain representations of the same equity (e.g., TSLAx, TSLAon, rTSLA) and trades via OKX DEX Router.

**Best for:** Portfolio tracking, equity research, risk analysis, automated rebalancing

### 2. Circle USDC Payments
**[Import Template](https://x.ai/bot/IX2bDYMLKqQhe1hYFnXdi)** | [Learn More](../templates/circle-usdc-payments/README.md)

Integrated with Circle App Kits for payment and liquidity workflows across 10+ blockchains with unified balance. Automate payroll, manage treasury, swap tokens, and earn yield.

**Best for:** Payments, payroll automation, treasury management, cross-chain transfers

### 3. Mezo Bitcoin Finance
**[Import Template](#)** | [Learn More](../templates/mezo-bitcoin-finance/README.md)

Equip your bot to run Bitcoin finance on Mezo. Mint MUSD against BTC collateral, stake in Stability Pool, monitor positions, and automate MUSD payments 24/7.

**Best for:** Bitcoin-backed lending, stablecoin generation, DeFi automation, payments

## Choosing the Right Template

| Need | Recommended Template |
|------|---------------------|
| Trade tokenized stocks/equities | Solana Tokenized Stocks |
| Send/receive USDC, automate payroll | Circle USDC Payments |
| Borrow stablecoins against BTC | Mezo Bitcoin Finance |
| Multi-role team coordination | Any template with multiple bots working together |

## Template Architecture

All templates include:
- **Agent Skills** - Pre-defined capabilities and instructions for the bot's role
- **MCP Server** - Tools to interact with blockchains, protocols, and APIs
- **Memory & Context** - Persistent memory for your bot to learn and coordinate
- **Workflow Instructions** - Built-in patterns for approvals, automation, and multi-agent tasks
