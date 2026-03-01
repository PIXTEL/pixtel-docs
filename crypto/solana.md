# Solana Integration

PIXTEL is built on **Solana**, one of the fastest and lowest-cost blockchains. The Solana integration enables wallet authentication, token interactions, and on-chain transactions directly from the game.

## Why Solana?

- **Fast transactions** — sub-second confirmation times
- **Low fees** — fractions of a cent per transaction
- **Phantom wallet** — the most popular Solana wallet, available as a browser extension
- **SPL Token standard** — PIXTEL token follows Solana's token standard

## What Solana Powers in PIXTEL

### Authentication

Players can sign in using their **Phantom wallet**. This creates a crypto-native account linked to their Solana address. Alternatively, players can enter as a **guest** without any wallet.

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

Shop purchases are made with PIXTEL tokens through the Solana blockchain:
- Transaction prepared by the backend
- Signed by the player through Phantom
- 50% of tokens are burned, 50% go to treasury
- Item is credited after on-chain confirmation

## No Wallet Required

PIXTEL does **not** require a crypto wallet to play. You can play as a **guest** without any account. The Solana integration is optional and adds crypto-native features for players who connect their Phantom wallet.
