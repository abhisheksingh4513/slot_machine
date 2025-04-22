# 🎰 Slot Machine Game (Node.js Console App)

A simple and interactive slot machine game built using Node.js for the terminal. The game allows users to deposit money, choose the number of lines to bet on, place bets, and spin to test their luck.

## 💡 Features

- Deposit funds to play
- Choose between 1 to 3 lines to bet on
- Spin a 3x3 slot machine with randomly distributed symbols
- Win based on matching symbols in each line
- Calculates and updates your balance after each round
- Play until you're out of balance or decide to stop

## 🛠️ Technologies Used

- Node.js
- `prompt-sync` (for synchronous terminal input)

## 📦 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/slot-machine-game.git
   cd slot-machine-game
npm install prompt-sync
node index.js

How to Play
Enter a deposit amount to load money into your balance.

Choose how many lines (1-3) you want to bet on.

Place your bet per line. The total bet will be bet × number of lines.

Spin the slot machine.

If all symbols in a line match, you win based on the symbol's value:

A = 5x bet

B = 4x bet

C = 3x bet

D = 2x bet

Your balance is updated, and you can choose to play again or quit.
Enter a deposit amount: 100
Enter the number of lines to bet on (1-3): 3
Enter the bet per line: 5
A | A | A
B | C | D
D | D | C
You won $75
You have a balance of $90
Do you want to play again (y/n)?
slot-machine-game/
│
├── index.js         # Main game logic
├── README.md        # Project description
└── package.json     # Dependencies and scripts
