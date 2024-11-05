# project11-slot-machine
## Slot Machine Project

This is a Python project that simulates a slot machine game. The player can set bets on different lines and try their luck to win based on matching symbols in the slot columns.

## Project Structure
- slot_machine.py: Main script that contains the game logic, including functions for setting up the slot columns, calculating winnings, and running the game.

## Features
- Bet Placement: Players can place bets on specific lines.
- Symbol Matching: Winnings are calculated based on matching symbols in the slot machine columns.
- Payout Calculation: Each symbol has a value, and winnings are multiplied by the bet amount.
  
## Game Rules
- The player selects the number of lines they want to bet on and places their bet.
- The slot machine generates random symbols across multiple columns.
- If all symbols in a chosen line match, the player wins based on the symbol’s value and the bet amount.
- The game ends when the player chooses to stop or runs out of funds.

## Usage
- Placing Bets: Enter the number of lines and the amount to bet when prompted.
- Checking Winnings: After each spin, winnings are displayed if there are matching symbols on any lines.
- Continuing or Exiting: Players can continue playing or exit the game based on their remaining funds.

## Functions
- check_winnings(columns, lines, bet, values): Checks for winning lines based on matching symbols and calculates winnings.
- spin_slot_machine(): Generates random symbols across columns.
- Additional helper functions for user input and game setup.
