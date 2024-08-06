

---

# Slot Machine Game 🎰

Welcome to the **Slot Machine Game**! This simple yet entertaining console-based slot machine game lets you experience the thrill of gambling without risking real money. Spin the reels, test your luck, and see if you can hit the jackpot!

## How to Play

The game is easy to play and follows these steps:

1. **Deposit Money:** Start by entering the amount of money you want to deposit into the game.
2. **Choose Lines:** Decide how many lines (1-3) you want to bet on. The more lines, the higher your chances of winning!
3. **Place Your Bet:** Enter your bet amount per line. Make sure you have enough balance to cover all lines.
4. **Spin the Slot Machine:** Spin the reels and watch the symbols align.
5. **Check Your Winnings:** If you get a matching row of symbols, you'll win based on the symbol values.
6. **Collect Your Winnings:** Your winnings will be added to your balance.
7. **Play Again:** If you have enough balance, you can choose to play again or cash out and end the game.

## Game Rules

- The slot machine has **3 rows** and **3 columns**.
- Symbols have different values:
  - **A**: Value of 5
  - **B**: Value of 4
  - **C**: Value of 3
  - **D**: Value of 2
- The number of each symbol in the reels:
  - **A**: 2
  - **B**: 4
  - **C**: 6
  - **D**: 8
- Winning is based on aligning symbols on the chosen lines.

## Try Out in Your Machine

To get started with the Slot Machine Game, follow these steps:

1. Ensure you have [Node.js](https://nodejs.org/) installed on your machine.
2. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/slot-machine-game.git
   ```

3. Navigate to the project directory:

   ```bash
   cd slot-machine-game
   ```

4. Install the required dependencies:

   ```bash
   npm install prompt-sync
   ```

5. Run the game:

   ```bash
   node index.js
   ```

## Gameplay Walkthrough

1. **Deposit Money:**
   - Enter the amount you want to start with. The game will prompt you until a valid amount is entered.

   ![Deposit Money](./images/deposit-money.png)

2. **Choose Lines to Bet On:**
   - Enter a number between 1 and 3 to select how many lines you want to bet on.

   ![Choose Lines](./images/choose-lines.png)

3. **Place Your Bet:**
   - Enter the bet amount for each line. Ensure your bet doesn't exceed your balance divided by the number of lines.

   ![Place Bet](./images/place-bet.png)

4. **Spin the Slot Machine:**
   - Watch as the reels spin and the symbols align.

   ![Spin Reels](./images/spin-reels.png)

5. **Check Winnings:**
   - If you have a winning line, your winnings are calculated and added to your balance.

   ![Check Winnings](./images/check-winnings.png)

6. **Play Again:**
   - Decide if you want to play another round or cash out.

   ![Play Again](./images/play-again.png)

## Symbol Values

Each symbol in the slot machine has a specific value that determines your winnings:

| Symbol | Value |
|--------|-------|
| A      | 5     |
| B      | 4     |
| C      | 3     |
| D      | 2     |

## Project Structure

- `slotGame.js`: The main file containing the game logic.
- `package.json()`: Contains the json file

## Features

- Interactive console-based gameplay.
- Customizable number of lines to bet on.
- Dynamic calculation of winnings based on symbol alignment.
- Real-time balance updates and betting system.
- Easy-to-understand prompts and user-friendly interface.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.
