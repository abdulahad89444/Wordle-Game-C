# Wordle Game

## Table of Contents

- [Description](#description)
- [Example](#example)
- [Getting Started](#getting-started)
- [Contributing](#contributing)

## Description

The Wordle game is a word guessing game where the player is asked to guess a 5-letter word in 6 tries. The game follows the following rules:

1. The player enters a 5-letter word as their guess.
2. The entered word is checked against a dictionary to ensure it is a valid word.
3. After a valid word is entered, it is compared against the solution.
4. Letters that are in their correct place compared to the solution are replaced by a '*'.
5. Letters that are present in the solution but are out of place are replaced by a '?'.
6. Letters that are not present in the solution are replaced with a hyphen '-'.

## Example

Let's take an example to understand the game better:

Solution word: Zonal (not case sensitive)

User Try 1: break
Program Output: ---*-

User Try 2: rolax
Program Output: -*?*-

User Try 3: sonar
Program Output: -***-

User Try 4: zonal
Program Output: *****   Correct! You Win!!

## Getting Started

To play the Wordle game, follow these steps:

1. Clone the repository.
2. Open the game in your preferred programming environment.
3. Run the game and start guessing words.
4. The program will provide feedback on each guess.
5. Keep guessing until you either win or run out of tries.

## Contributing

Contributions to the Wordle game are welcome! If you have any ideas for improvements or new features, feel free to submit a pull request.


"# Wordle-Game-C" 
