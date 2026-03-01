# Fireplace & Burning

The **Fireplace** is a deflationary mechanism in PIXTEL that lets players permanently destroy PIXTEL tokens, reducing the circulating supply.

## How It Works

1. **Find the Fireplace** in the hotel (look for the fire animation)
2. **Click** to open the burn panel
3. **Enter the amount** of PIXTEL tokens you want to burn
4. **Confirm** the transaction through your Phantom wallet
5. Tokens are burned on-chain and permanently destroyed

## 100% Burn

All tokens sent to the Fireplace are **permanently destroyed**. 100% of the burned amount is removed from circulation — nothing goes to treasury or any other wallet.

```
PIXTEL Tokens ──► Fireplace ──► 100% Burned (permanently destroyed)
```

## On-Chain Verification

Every burn transaction is:
- Verified on the **Solana blockchain**
- Tracked with a unique **burn record** in the database
- Protected by **idempotency keys** (prevents double-crediting)
- Signed through your **Phantom wallet** (you always control the transaction)

## Burn Records

Each burn is recorded with:
- Amount burned (in atomic units)
- Solana transaction signature
- Timestamp

You can view your burn history through the Fireplace panel.

## Why Burn?

- **Reduce supply** — burning removes tokens from circulation permanently
- **Deflationary** — every burn increases scarcity of the PIXTEL token
