# Fireplace & Burning

The **Fireplace** is a special feature in PIXTEL that lets players burn PIXTEL tokens in exchange for in-game rewards.

## How It Works

1. **Find the Fireplace** in the hotel (look for the fire animation)
2. **Click** to open the burn panel
3. **Enter the amount** of PIXTEL tokens you want to burn
4. **Confirm** the transaction through your Phantom wallet
5. Tokens are burned on-chain and you receive rewards

## Burn Threshold

To receive a **gift reward**, you need to burn at least **100,000 PIXTEL tokens** in a single transaction.

Burns below this threshold still count toward the total but won't trigger an immediate reward.

## Revenue Distribution

When tokens are burned through the Fireplace:

| Revenue Type | Burn % | Treasury % |
|-------------|--------|------------|
| Item/Room purchases | 50% | 50% |
| XIPS purchases | 0% | 100% |

- **Burn** = tokens are permanently destroyed (removed from circulation)
- **Treasury** = tokens go to the XIPS treasury for ecosystem funding

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
- Reward granted (if any)

You can view your burn history through the Fireplace panel.

## Why Burn?

- **Earn rewards** — gifts and special items
- **Reduce supply** — burning removes tokens from circulation permanently
- **Support the ecosystem** — treasury funds go toward game development and XIPS backing
