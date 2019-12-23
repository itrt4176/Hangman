# Hangman
Training project to learn java.

## Requirements
- Visual Studio Code
- JDK 11

## Setup
1. Download repository as a zip file from GitHub
2. Extract into an empty folder
3. In VSCode, go to File>Open Folder...
4. Select the folder you had previously extracted the zip into
5. Click Select Folder

## Objective
Write a reverse Hangman game in which the user thinks of a word and the computer
tries to guess the letters in that word. The user tells the computer how many letters
the word contains.

Your program must output what the computer guessed on each turn, and show the
partially completed word. It also must use pseudorandom functions to make
guesses. That is, it should not simply try all the letters in order, nor should it use the
user’s input to its advantage.

### Output
```
Enter a word for me to guess: Hello world
I guess: X  _____ _____
I guess: N  _____ _____
I guess: L  __LL_ ___L_
I guess: T  __LL_ ___L_
I guess: D  __LL_ ___LD
I guess: H  H_LL_ ___LD
I guess: I  H_LL_ ___LD
I guess: R  HELL_ __RLD
I guess: Z  HELL_ __RLD
I guess: O  HELLO _ORLD
I guess: W  HELLO WORLD
```
