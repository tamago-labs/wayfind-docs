# Trading with OKX DEX

Execute tokenized stock swaps through OKX DEX Router directly from your bot with approval workflows.

## How It Works

1. **Get Quote** - Your bot finds the best route across liquidity sources
2. **Review** - Bot prepares the trade details for your approval (amounts, fees, route)
3. **Approve** - You confirm the trade
4. **Execute** - Bot signs and sends the transaction via OKX DEX Router
5. **Confirm** - Transaction hash returned for tracking

## Features

- **Best Price Routing** - OKX DEX aggregates liquidity across multiple sources
- **Solana Mainnet** - Trading currently available on Solana mainnet
- **Approval Required** - All trades require your explicit approval
- **Real Swaps** - Executed onchain with real transactions
- **Multi-Representation** - Can route between different versions of the same stock

## Example Use Cases

- "Swap 100 USDC for TSLAx" - Buy tokenized Tesla
- "Rebalance my portfolio" - Bot prepares rebalancing trades for approval
- "Find best price for AAPL" - Compare prices across different token representations

## Proven Usage

Wayfind has executed real swaps on Solana mainnet through OKX DEX Router, including:
- SpaceX xStock (SPCXx)
- Anduril via PreStocks
