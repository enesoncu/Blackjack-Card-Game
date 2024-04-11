# Project Title: Blackjack Card Game

## Description
This Python script brings the thrill of Blackjack to your terminal! Test your luck and card-counting skills as you go head-to-head with the dealer in this classic casino game. Can you strategically draw cards and build a hand closer to 21 without going bust?

## Features
- Interactive gameplay with clear user prompts.
- Immersive ASCII art logo for a touch of casino flair (requires art library).
- Simulates dealing cards from a standard deck using random selection.
- Calculates card values accurately, handling aces as 1 or 11.
- Tracks user and computer scores to determine the winner.
- Implements the Blackjack rule of converting aces to 1s if the total score exceeds 21.
- Compares scores and announces the winner (user, computer, or draw) based on Blackjack rules.
- Offers the option to play multiple rounds with a user-friendly "play again" prompt.

## How to Play
**1- Run the Script:** Execute the script using python **"blackjack_card_game.py"** in your terminal.

**2- Start the Game:** Choose "y" to begin a round of Blackjack.

**3- Deal Cards:** You and the computer are each dealt two cards. Your cards and current score are displayed, while you see only the computer's first card.

**4- Hit or Stand:** Decide whether to "y" for another card (hit) or "n" to stop drawing (stand). Strategize to build your hand closer to 21 without exceeding it.

**5- Computer's Turn:** The computer automatically draws cards until its score reaches 17 or higher.

**6- Compare Scores:** The script determines the winner based on Blackjack rules, considering scores, busting, and Blackjacks (21 with two cards).

**7- Play Again (Optional):** If you wish to play another round, type "y" at the prompt.

## Example Gameplay
Your cards: [10, 5], current score: 15

Computer's first card: [3]

Do you want to get another card, type 'y' or type 'n' to pass: y

Your cards: [10, 5, 7], current score: 22

You went over. You lose 

Do you want to play a game of Blackjack? Type 'y' or 'n': y

## Contributing

Feel free to contribute to this project by:

- Implementing visual elements for the cards and user interface (e.g., with libraries like colorama).
- Adding sound effects for card dealing and game events.
- Expanding the functionality to include betting and chip management.

To contribute, fork the repository on GitHub and create a pull request with your proposed changes.


## Dependencies
This script optionally uses the **"art"** library for the ASCII art logo. To install it, run **"pip install art"** in your terminal before playing.
