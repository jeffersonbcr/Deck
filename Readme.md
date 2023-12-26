# Go Card Deck Project

## Project Overview

This Go project creates a simple card deck management system. It includes functionalities like creating a new deck of cards, shuffling, printing, saving to a file, and loading from a file. The project is structured across three main files: `main.go`, `deck.go`, and `deck_test.go`.

## Files Description

### main.go
This is the entry point of the application. It demonstrates how to create a new deck, shuffle it, and print the cards.

### deck.go
This file defines the core functionalities and data structures. Key components include:
- `deck` type: A custom type based on a slice of strings, representing a deck of cards.
- `newDeck()`: A function to create and return a new deck of cards.
- `(d deck) print()`: A method to print each card in the deck.
- `deal(d deck, handsize int)`: A function to split the deck into two parts.
- `(d deck) toString()`: A method to convert the deck into a string representation.
- `(d deck) saveToFile(filename string)`: A method to save the deck to a file.
- `newDeckFromFile(filename string)`: A function to create a deck from a saved file.
- `(d deck) shuffle()`: A method to shuffle the deck randomly.

### deck_test.go
Contains unit tests for the application, ensuring the correctness of the deck functionalities like creating a new deck, checking its size, the first and last cards, and the save/load from file feature.

## Setup and Execution

To run this project, you need to have Go installed on your system. Clone the repository and navigate to the project directory. Run the application using the command:

```bash
go run main.go deck.go
```

To run test:

```bash
go test
```

# Autores

<a href="https://github.com/jeffersonbcr">
    <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/58866006?v=4" width="100px;" alt=""/><br />
    <sub><b>Jefferson Botitano</b></sub></a><br />