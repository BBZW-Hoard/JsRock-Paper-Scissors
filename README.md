# M293 JsWebsite

## Scissors, Stone, Paper

"Scissors, Stone, Paper" is an old game where two people each choose a symbol and then display (or say) it simultaneously. If both players have the same symbol, the round is a tie. Otherwise, the following rules apply:

- Scissors cuts paper - and wins the round.
- Paper wraps stone - and wins the round.
- Stone dulls scissors and wins.
Thus, we have written down the rules for "Scissors, Stone, Paper". Now we need to think about how our program should look around this game. We need to determine how many rounds we want to play and what criteria should apply for a victory (over multiple rounds played).

We simply determine that the number of rounds should be unlimited. However, if a player wins three times (in total, not necessarily in a row), then the game is over and the winner is determined.

## And how do you program that now?

Think about in your own words what the program should do.

## Example

At the beginning of each round, the computer decides what it will do. Then you enter what you choose. It then compares who won the round. If both have the same symbol, the round is a tie. Scissors wins against paper, paper wins against stone, and stone wins against scissors. If someone has won three times, the game ends. Then it will be output who has won how many times.

# Task

Program the game. **The game may run on the console.**
For outputs, you can use `alert()` and for inputs `prompt()`.
Note: After each round, it will be decided if there is a winner. (foot-controlled loop).

---

This Project is a license under the MIT License - see the [LICENSE](LICENSE) file for details.
