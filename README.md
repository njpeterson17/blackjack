# Blackjack Game

A command-line Blackjack game written in Python. Play against the dealer, place bets, and try to beat the house!

## Features

- 🎮 Classic Blackjack rules
- 💰 Betting system with starting bankroll
- 🃐 Multiple decks (configurable)
- 📊 Statistics tracking
- 🎯 Dealer AI follows standard casino rules
- 💾 Persistent player stats

## How to Play

### Option 1: Web Browser (Easiest)
Open `index.html` in your browser:
```bash
# Just double-click index.html or:
open index.html        # Mac
xdg-open index.html    # Linux
start index.html       # Windows
```

Or play online: [GitHub Pages Link](https://njpeterson17.github.io/blackjack)

### Option 2: Command Line
```bash
python blackjack.py
```

### Rules
- Start with $1000 bankroll
- Place your bet each round
- Try to get closer to 21 than the dealer without busting
- Dealer hits on 16 and stands on 17
- Blackjack pays 3:2

### Controls
- `h` - Hit (take another card)
- `s` - Stand (keep current hand)
- `d` - Double down (double bet, take one more card)
- `q` - Quit game

## Installation

```bash
git clone https://github.com/nockpoterson/blackjack.git
cd blackjack
python blackjack.py
```

## Requirements

- Python 3.6+

## License

MIT License - feel free to use and modify!

---

*Remember: The house always wins... eventually.* 🎰