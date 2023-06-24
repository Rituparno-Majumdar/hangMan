Getting Started

To use the Hangman game script, follow these steps:

1. Make sure you have Python installed on your system.
2. Clone or download the repository.

Prerequisites

Python 3.x

Usage

1. Open a terminal or command prompt.
2. Navigate to the directory where the code file is located.
3. Run the following command to execute the script:python hangMan.py

The program will randomly select a word from a predefined list. Your task is to guess the letters in the word correctly. 
You have a limited number of lives, and each incorrect guess will decrease your remaining lives. The program will display 
the current state of the word with underscores representing the unguessed letters.

Example gameplay:

 _                                             
| |                                            
| |__   __ _ _ __   __ _ _ __ ___   __ _ _ __  
| '_ \ / _` | '_ \ / _` | '_ ` _ \ / _` | '_ \ 
| | | | (_| | | | | (_| | | | | | | (_| | | | |
|_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|
                    __/ |                      
                   |___/    
Please guess a letter: a
You guessed a, that's not in the word. You lose a life, You have 5 life left. 
_ _ _ _ _ _ _

  +---+
  |   |
  O   |
      |
      |
      |
=========

Please guess a letter: c
You guessed c, that's not in the word. You lose a life, You have 4 life left. 
_ _ _ _ _ _ _

  +---+
  |   |
  O   |
  |   |
      |
      |
=========

Please guess a letter: b
You guessed b, that's not in the word. You lose a life, You have 3 life left. 
_ _ _ _ _ _ _

  +---+
  |   |
  O   |
 /|   |
      |
      |
=========
Please guess a letter: r
You guessed r, that's not in the word. You lose a life, You have 2 life left. 
_ _ _ _ _ _ _

  +---+
  |   |
  O   |
 /|\  |
      |
      |
=========

Please guess a letter: h
You guessed h, that's not in the word. You lose a life, You have 1 life left. 
_ _ _ _ _ _ _

  +---+
  |   |
  O   |
 /|\  |
 /    |
      |
=========

Please guess a letter: l
You guessed l, that's not in the word. You lose a life, You have 0 life left. 
You lose! 
_ _ _ _ _ _ _

  +---+
  |   |
  O   |
 /|\  |
 / \  |
      |
=========


Process finished with exit code 0

Feel free to modify the code or incorporate it into your own projects. Enjoy playing Hangman!

Contribution

If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.
Contributions are highly welcome!

Contact

If you have any questions or need further assistance, please feel free to contact the project maintainer at
majumdarrituparno@gmail.com.

Thank you!