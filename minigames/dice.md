# Dice

Dice is PIXTEL's classic multiplayer betting minigame. Simple to learn, fast-paced, and supports up to 4 players.

## Overview

| Detail | Value |
|--------|-------|
| Players | 2 - 4 |
| Turn timer | 25 seconds |
| Bet range | 50,000 - 10,000,000 XIPS |
| Type | Turn-based |

## How It Works

### 1. Setup

The **host** creates the table by choosing:
- Minigame type: Dice
- Bet amount (all players bet the same amount)

Other players walk up to the table and click **Join**. Each player's bet is deducted from their XIPS balance immediately upon joining.

### 2. Ordering Phase

Before the main round starts, all players roll dice to **determine the turn order**. The player with the highest roll goes first.

This phase is automatic — each player rolls once, and the order is set.

### 3. Main Round (Started Phase)

Players take turns rolling two dice:

- On your turn, click the **Roll** button (or wait for auto-roll)
- Two dice are rolled (values 1-6 each)
- Your total (2-12) is recorded
- The turn passes to the next player

Each player's results are displayed on a score grid visible to everyone at the table.

### 4. Winning

The player with the **highest dice total** at the end of the minigame wins the entire pot.

## Features

### Auto-Roll

If you don't roll within the turn timer, the system will automatically roll for you. There's also a configurable auto-roll option with a countdown.

### Turn Timer

Each player has **25 seconds** to make their roll. A visual timer bar shows the remaining time, changing from green to red as time runs out.

### Live Updates

All players see dice results in real time. When another player rolls, you'll see:
- Their dice values animated on screen
- The score grid updating
- Turn indicator moving to the next player

### Host Controls

The host (table creator) can:
- Start the minigame when enough players have joined (minimum 2)
- The minigame will not start until the host presses **Start**

## Pot Distribution

- All player bets are pooled into a shared **pot**
- The winner receives the **entire pot**
- If a player leaves during an active minigame, they forfeit their bet

## Tips

- The minimum roll is 2 (two ones) and the maximum is 12 (two sixes)
- Dice is pure luck — every player has the same odds
- The pot grows with more players, making 4-player minigames the most rewarding
