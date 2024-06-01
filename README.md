
# Slot Machine Game

This is a simple command-line slot machine game implemented in Python. Players can deposit money, place bets on a number of lines, and spin the slot machine to potentially win more money.


## How to Run

1.Ensure you have Python installed on your machine.

2.Save the script to a file, for example, slot_machine.py.

3.Open a terminal and navigate to the directory containing the script.

4.Run the script using the command:
```bash
  python slot_machine.py
```
## Game Instructions

Depositing Money

- The game starts by prompting you to deposit an amount of money. 

- This will be your starting balance.

Placing Bets

- You can place bets on 1 to 3 lines.

- You will be asked to enter the number of lines you want to bet on.

- Next, you will be prompted to enter the amount you wish to bet on each line. 

- The bet amount must be between $1 and $100.

- Spinning the Slot Machine

- Once you place your bet, the slot machine will spin.

- The slot machine has 3 rows and 3 columns with symbols "A", "B", "C", and "D".

- Each symbol has a different count and value:

   - "A" appears 2 times and is worth $5.

   - "B" appears 4 times and is worth $4.

   - "C" appears 6 times and is worth $3.

   - "D" appears 8 times and is worth $2.

Winning

- If you get the same symbol across any of the lines you bet on, you win an amount equal to the symbol's value multiplied by your bet.

- Your winnings are added to your balance, and your total bet is subtracted.

Quitting the Game

- You can quit the game at any time by pressing 'q' when prompted.

- Your final balance will be displayed when you quit the game.

