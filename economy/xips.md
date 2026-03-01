# XIPS Currency

**XIPS** is the primary in-game currency of PIXTEL. It powers the entire game economy — from betting on games to buying items in the shop.

## What Are XIPS?

XIPS is the virtual currency used inside PIXTEL. It's not a blockchain token — it's an in-game balance tracked on the server.

Every player starts with an initial XIPS balance and can earn more through gameplay.

## How to Earn XIPS

| Method | Description |
|--------|-------------|
| **Win games** | Win Dice or Pool matches to take the pot |
| **Token burning** | Burn PIXTEL tokens at the Fireplace to receive XIPS |
| **Purchase** | Buy XIPS packages from the shop |

## How to Spend XIPS

| Use | Description |
|-----|-------------|
| **Game bets** | Bet XIPS when creating or joining a game table (50K - 10M range) |
| **Shop items** | Buy furniture, pool cues, and cosmetics |
| **Room features** | Some premium room features require XIPS |

## Balance

Your XIPS balance is displayed in the game UI at all times. It updates in real time when you:

- Win or lose a game
- Make a purchase
- Receive XIPS from burning tokens

## Game Economy Flow

```
Player A bets 100,000 XIPS ──┐
                              ├──► Pot: 200,000 XIPS ──► Winner takes all
Player B bets 100,000 XIPS ──┘
```

All game transactions are **server-authoritative** — the backend validates every bet, deduction, and payout to prevent cheating.

## Security

- XIPS balances are stored server-side (Firebase)
- All transactions go through Cloud Functions with validation
- Bet deductions happen atomically (your balance is checked and deducted in a single operation)
- Refunds are issued automatically if a game is cancelled while in "waiting" status
