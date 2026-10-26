# FAQ

## General

### What is Wayfind?
Wayfind is the platform for building always-on Web3 bot teams. Each bot template comes with an agentic wallet and multi-chain access, so your bots can track tokenized stocks, manage USDC payments, or coordinate onchain tasks across Solana and EVM chains.

### Do I need Grok Bot to use Wayfind?
No — Wayfind works with any AI agent of your choice. Each template includes agent skills and instructions to import into platforms like Claude Code, Cursor, OpenCode, Cherry Studio, or others. Just follow the included setup guide. Grok Bot offers the easiest one-click import experience.

### Which chains does Wayfind support?
Wayfind supports Solana and multiple EVM chains including Ethereum, Base, Arbitrum, Polygon, Avalanche, Optimism, World, Sei, and Arc. One agentic wallet works across all of them, depending on the template you're using.

## Setup & Wallets

### How do I set up Wayfind on Grok Bot?
Download a Grok Bot template from [wayfind.click](https://wayfind.click/) and set your `WALLET_PASSKEY` environment variable on the bot computer. The bot creates an agentic wallet on first run with multi-chain access. An API key is optional for some templates.

### Is my wallet safe?
Your wallet seed stays on the bot computer. It is protected by your `WALLET_PASSKEY` and never shared with Wayfind. Anyone with access to that machine and your passkey can move funds, so keep both secure.

## Templates

### How does Wayfind handle tokenized stocks?
Wayfind indexes tokenized stocks so your bots can track and trade them via OKX DEX Router. Trading is available on Solana mainnet. You will need an API key to access the data and execute trades through the Solana Tokenized Stocks template.

### How is TSLAx different from TSLAon?
One company like Tesla can have multiple onchain representations — TSLAx, TSLAon, rTSLA — each with different prices, liquidity, and issuers. Wayfind lists every version so you can compare and trade the best option.

### What can I do with the Circle USDC Payments template?
You can send and receive USDC across 10+ chains with unified balance, swap tokens via Circle Swap Kit, earn yield through vaults like Morpho, and automate payroll/treasury workflows with multi-agent coordination.

### What can I do with the Mezo Bitcoin Finance template?
You can borrow MUSD against BTC collateral (min 110% collateralization), stake MUSD in the Stability Pool for yield, monitor positions with ICR alerts, automate position management, and schedule MUSD payments. Currently available on Mezo Testnet.

## AI Features

### What does the risk score mean?
Your risk score is a personalized view of the risk in your portfolio based on your holdings, market conditions, and risk profile. Wayfind also breaks the score down into the factors contributing to it, so you can understand what is driving your portfolio risk.

### What can I do with Wayfind after the risk analysis?
Wayfind turns the risk analysis into actionable options. Depending on your portfolio and goals, you may see ways to reduce concentration, rebalance your holdings, diversify exposure, or put eligible assets to work through available DeFi opportunities.

### How do AI credits work?
AI credits power deeper analysis and AI-powered features in Wayfind (like AI Risk Review and Chat Further). New users get 1,000 free credits. Credit usage depends on the complexity of the analysis, and available credits can be managed from your dashboard. All AI operations deduct credits at $0.01 per token (input + output).
