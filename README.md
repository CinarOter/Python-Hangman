# Python Hangman Game

I made this simple Python Hangman game to practice programming and have some fun with text-based games. The program picks a random word from a list, and you try to guess it one letter at a time. As you make wrong guesses, a stick hangman is drawn to show your progress.

I built this project to practice using loops, conditionals, functions, and sets. It also taught me how to manage game state, handle user input, and give players visual feedback using text.

**Key Features**
* Randomly chooses a word from a list
* Shows hints with underscores for letters you haven’t guessed yet
* Displays a hangman that updates with each wrong guess
* Keeps track of letters you’ve already guessed
* Lets you win by guessing the word or lose if the hangman is fully drawn

**How to Play**
* The game picks a random word from the word list
* Enter one letter at a time to try and guess the word
* Correct letters are revealed in the hint
* Wrong letters make the hangman progress
* You win if you guess the word before the hangman is complete
* You lose if the hangman is fully drawn first

**Example Gameplay**
Current word: _ _ _ _ _  
Enter a letter: a  
Correct! The word now looks like: _ a _ _ _  

Current word: _ a _ _ _  
Enter a letter: e  
Wrong guess! The hangman progresses.

