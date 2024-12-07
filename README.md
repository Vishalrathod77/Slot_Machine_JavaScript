# Slot Machine Game

A simple command-line slot machine game implemented in JavaScript where players can try their luck by betting on multiple lines.

## Description

This is a text-based slot machine game where players can:
- Deposit money
- Choose the number of lines to bet on (1-3)
- Place bets per line
- Spin the slot machine
- Win based on matching symbols

## Game Features

- 3x3 grid slot machine
- Four different symbols (A, B, C, D) with varying frequencies and values
- Multiple betting lines
- Balance management system
- Continuous gameplay option

## Symbol Values
- A: 5x multiplier (rare)
- B: 4x multiplier
- C: 3x multiplier
- D: 2x multiplier (common)

## How to Play

1. Run the game using Node.js
2. Enter your initial deposit
3. Choose number of lines to bet on (1-3)
4. Enter your bet amount per line
5. Watch the slots spin
6. Collect winnings if you match symbols
7. Choose to continue playing or exit

## Requirements

- Node.js
- prompt-sync package

## Installation

1. Make sure Node.js is installed on your system
2. Install the required package:
   ```bash
   npm install prompt-sync
   ```

## Running the Game

```bash
node project.js
```

## Game Rules

- You must bet on at least 1 line and can bet up to 3 lines
- Your bet per line cannot exceed your available balance divided by the number of lines
- Winning combinations are formed when all symbols in a betting line match
- Winnings are calculated based on the bet amount multiplied by the symbol value
- Game continues until you run out of money or choose to stop playing
