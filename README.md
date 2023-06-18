# Game of War
Game of War is a simple web-based card game where players draw cards from a shuffled deck and compare their values to determine the winner of each round.

## Features
New Deck Button: Clicking the "New Deck" button fetches a new shuffled deck of cards from an external API and displays the number of remaining cards.
Draw Cards Button: Clicking the "Draw" button fetches two cards from the deck and displays them on the webpage. The values of the drawn cards are compared to determine the round winner.
Scores: The computer score and player score are displayed and updated based on the outcome of each round.

Winner Display: If there are no remaining cards, the final winner (computer or player) is displayed in the header.

## Technologies Used
HTML: Markup language for structuring the webpage.
CSS: Styling language for visual presentation.
JavaScript: Programming language for implementing interactivity and fetching data from APIs.

## API Integration
The website utilizes the "Deck of Cards" API provided by https://apis.scrimba.com/deckofcards/ to fetch and shuffle the deck of cards, as well as draw cards from the deck.

## Setup and Usage
Clone or download the project files to your local machine.
Open the index.html file in a web browser.
Click the "New Deck" button to start a new game and fetch a shuffled deck.
Click the "Draw" button to draw two cards and compare their values.
Repeat step 4 until there are no remaining cards.
The winner of the game will be displayed in the header.

## Credits
The "Deck of Cards" API: https://apis.scrimba.com/deckofcards/

## License
This project is licensed under the MIT License.