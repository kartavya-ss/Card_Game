# 🃏 Card Game – Smart Dealing & Gameplay Simulation

A Python-based simulation of a customizable card game featuring shuffling, dealing, and hand evaluation mechanics.

---

## 📂 Project Overview

This project implements core logic for a card game:
- Deck creation with 52 standard playing cards
- Shuffling algorithm to randomize the deck
- Dealing cards to players
- Evaluating the best hands (e.g., pairs, straights, flushes)
- Simulating player interactions and simple AI-based decisions

---

## ✅ Features

- Deck represented with suits and ranks
- Efficient Fisher–Yates shuffling
- Flexible dealing: configurable number of players and cards per hand
- Hand evaluation logic (e.g., pair, three-of-a-kind, straight)
- Game simulation and logging to track results

---

## 🛠️ Getting Started

### Prerequisites

Install the required Python libraries:

```
pip install numpy
```

📊 Example Output
```
Sample session output:
Shuffled deck.
Dealt 5 cards each to 4 players.
Player 1 hand: ['2♠', '10♦', 'J♣', 'J♦', '5♥'] → Pair: Jacks
Player 2 hand: ['3♠', '4♣', '5♣', '6♦', '7♠'] → Straight
...
Winning hand: Player 2 with a Straight!
```

🔮 Future Improvements

•Support more complex hands (e.g., full house, flush)

•Implement betting logic or turn-based actions

•Add GUI or web interface using Tkinter or Flask

•Extend game rules for multiplayer online gameplay

