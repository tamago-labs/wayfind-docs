# Borrowing MUSD

Borrow MUSD against BTC collateral on Mezo.

## How It Works

1. **Deposit BTC** - Add BTC as collateral to your trove
2. **Open Trove** - Create a position with minimum 110% collateralization ratio
3. **Mint MUSD** - Borrow MUSD at fixed 1% interest rate
4. **Manage** - Add/withdraw collateral, repay debt, or close anytime

## Requirements

- **Minimum Collateralization** - 110% ICR required
- **Interest Rate** - Fixed 1% on borrowed MUSD
- **Collateral** - BTC on Mezo network

## Example

```
Deposit 0.03 BTC → Borrow ~1800 MUSD (at 110% ICR)
```

## Using with Your Bot

- "Open a trove with 0.01 BTC" - Create new position
- "How much MUSD can I borrow?" - Calculate borrowing capacity
- "Add collateral to my trove" - Increase collateralization
- "Repay MUSD debt" - Pay back borrowed amount
- "Close my trove" - Withdraw collateral and repay debt
