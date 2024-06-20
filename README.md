# Jupyter Notebook Hangman Game

An interactive and animated Hangman game implemented in Python, designed to run in a Jupyter Notebook environment.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [How to Play](#how-to-play)
- [Customization](#customization)
- [Contributing](#contributing)


## Description

This Hangman game is built using Python and leverages Jupyter widgets to create an interactive and visually appealing gaming experience. The game features an animated hangman figure, dynamic word display, and real-time feedback, all within a Jupyter Notebook.

## Features

- Dynamic word display with letter reveal
- Real-time feedback on guesses
- Customizable word list
- Interactive input via Jupyter widgets
- Responsive design for various screen sizes

## Requirements

- Python 3.6+
- Jupyter Notebook or JupyterLab

## Installation

1. Clone this repository:git clone https://github.com/HarshKumat/Hangman-Game.git


## Usage

1. Start Jupyter Notebook:

2. Open the `Hangman_Game.ipynb` notebook.

3. Run all cells in the notebook to start the game.

## How to Play

1. The game will select a random word from the provided word list.
2. Guess one letter at a time by typing into the input box and clicking "Submit" or pressing Enter.
3. Correct guesses will reveal the letter in the word.
4. Incorrect guesses will add a part to the hangman figure.
5. You win if you guess the word before the hangman is completed.
6. You lose if the hangman figure is completed before you guess the word.

## Customization

- To use your own word list, replace the content of `words.txt` with your desired words, one word per line.
- Adjust the `max_attempts` variable in the `HangmanGame` class to change the difficulty.
- Modify the CSS in the `display_game` method to change the game's appearance.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
