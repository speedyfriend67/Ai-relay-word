# Word Relay with AI

Welcome to the Word Relay with AI game! This simple web application allows you to play a word relay game with an AI opponent.

## How to Play

1. Enter a word in the input field and click the "Play" button.
2. The AI will respond with a word that starts with the last letter of your word.
3. Continue taking turns with the AI, each time entering a word that starts with the last letter of the AI's word.

## Rules

- Words must be at least 3 letters long.
- Players cannot repeat words that have already been used.
- The AI will attempt to generate words using the Datamuse API based on the last letter of the user's word.

## Log Management

- Use the "Delete Last Word" button to remove the last word from the log list.
- Use the "Clear All" button to clear the entire log list.

## Getting Started

To run the application, simply open the `index.html` file in a web browser.

## Technologies Used

- HTML
- CSS
- JavaScript

## Credits

- The AI uses the Datamuse API for word suggestions.
- @Hvven for the 85 line fix

## License

This project is licensed under the [MIT License](LICENSE).
