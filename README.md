# Spanish Flashcards

**Overview**

This project is a basic flashcard game designed to help users learn Spanish vocabulary. It was created using Python, with the help of the pandas library for data manipulation and tkinter for the graphical user interface.

**Features**

- Interactive Flashcards: Presents Spanish words and lets you guess the English translation.
- Easy-to-Use Interface: Simple graphical user interface built with tkinter.
- Progress Management: Pressing the check mark button removes correctly guessed words from the list.
- Learning Reinforcement: Words not guessed correctly are saved to a file (words_to_learn.csv) and will be revisited in future sessions.

**How to Play**

- Start the Game: Launch the application to start the flashcard game.
- Guess the Word: A Spanish word will be displayed. Try to guess its English translation.
- Check Your Answer: Press the check mark button if you guessed the word correctly.
- Update Your Progress: Correctly guessed words are removed from the list. Words you didn't guess correctly are saved to words_to_learn.csv.
- Learn New Words: The game updates with new words to learn based on your progress.

**File Structure**

main.py: Main script to run the flashcard game.
spanish_words.csv: Initial list of Spanish words and their English translations.
