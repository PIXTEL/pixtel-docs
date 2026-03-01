# Solana Integration

PIXTEL is built on **Solana**, one of the fastest and lowest-cost blockchains. The Solana integration enables wallet authentication, token interactions, and on-chain transactions directly from the game.

## Why Solana?

- **Fast transactions** — sub-second confirmation times
- **Low fees** — fractions of a cent per transaction
- **Phantom wallet** — the most popular Solana wallet, available as a browser extension
- **SPL Token standard** — PIXTEL token follows Solana's token standard

## What Solana Powers in PIXTEL

### Authentication

Players can sign in using their **Phantom wallet** instead of email. This creates a crypto-native account linked to their Solana address.

### Token Holding

The game checks your wallet for **PIXTEL token** holdings. Token holders get access to:
- Public room creation
- Exclusive features

### Token Burning

The [Fireplace](../economy/fireplace.md) feature burns PIXTEL tokens on-chain:
- Transactions are executed on Solana mainnet
- Burns are verified using the **Memo program**
- Transaction signatures are stored for audit

### Shop Purchases

Premium purchases (XIPS packages) go through the Solana blockchain:
- Transaction prepared by the backend
- Signed by the player through Phantom
- Confirmed on-chain before crediting the account

## Technical Details

| Component | Detail |
|-----------|--------|
| Network | Solana Mainnet |
| Wallet | Phantom (browser extension) |
| Token Standard | SPL Token |
| Memo Program | `MemoSq4gqABAXKb96qnH8TysNcWxMyWCqXgDLGmfcHr` |
| Signing | TweetNaCl (Ed25519) |

## No Wallet Required

PIXTEL does **not** require a crypto wallet to play. You can create a regular account with email and enjoy the full game. The Solana integration is optional and adds crypto-native features for users who want them.
