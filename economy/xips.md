# XIPS Currency

**XIPS** is an alternative off-chain currency to the PIXTEL token. It only exists inside the game and is currently used for minigames.

## What Are XIPS?

XIPS is a virtual currency that works **entirely off-chain** — it's not a blockchain token, but an in-game balance tracked on the server.

The main advantage of XIPS is that **no transaction fees are required** when using it. Since PIXTEL token transactions go through the Solana blockchain, they incur gas fees. XIPS avoids this by operating off-chain, making minigame betting instant and free of network costs.

## How to Get XIPS

| Method | Description |
|--------|-------------|
| **Swap** | Exchange PIXTEL tokens for XIPS in the in-game Swap |
| **Win minigames** | Win Dice or Pool matches to take the pot |

These are the only two ways to obtain XIPS.

## How XIPS Are Used

XIPS are currently used exclusively for **minigame betting**:

| Use | Description |
|-----|-------------|
| **Minigame bets** | Bet XIPS when creating or joining a minigame table (50K - 10M range) |

## Balance

Your XIPS balance is displayed in the game UI at all times. It updates in real time when you:

- Win or lose a minigame
- Swap PIXTEL tokens for XIPS

## Economy Flow

```
PIXTEL Token ──► Swap ──► XIPS (off-chain)

Player A bets 100,000 XIPS ──┐
                              ├──► Pot: 200,000 XIPS ──► Winner takes all
Player B bets 100,000 XIPS ──┘
```

All minigame transactions are **server-authoritative** — the backend validates every bet, deduction, and payout to prevent cheating.

## XIPS vs PIXTEL Token

| | XIPS | PIXTEL Token |
|--|------|-------------|
| **Type** | Off-chain (in-game only) | On-chain (Solana SPL token) |
| **Transaction fees** | None | Solana network fees |
| **Used for** | Minigame bets | Shop purchases, Fireplace, Swap |
| **How to get** | Swap or win minigames | DEX, community events |

## Security

- XIPS balances are stored server-side (Firebase)
- All transactions go through Cloud Functions with validation
- Bet deductions happen atomically (your balance is checked and deducted in a single operation)
- Refunds are issued automatically if a minigame is cancelled while in "waiting" status
