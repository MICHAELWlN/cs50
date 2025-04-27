## meteor-dodge
 First game project using scratch. Player controls a rocketship while dodging meteors.
 
 ## What It Does:
 You control a spaceship using the left and right arrow keys and attempt to avoid falling meteors. If a meteor hits your spaceship, the game ends with a sound effect and a message.
 
 ## What I learned
 -Conditionals and loops to control behavior
 -Detecting collision in Scratch
 -Using events like when "when green flag clicked"
 -Basic game design structure
 
 ## How to Play
 -Press the Green Flag
 -Use left arrow key to move left, right arrow key to move right
 -Don't get hit by the meteor
 
 ## Live Scratch Game
 https://scratch.mit.edu/projects/1159248382 

 # Week 1: Hello, World & Mario C Assignments
These are my first C programs I wrote for cs50. The goal of these assignments were to get familiar with writing, compiling, and running a program in C.

# What it does: This program prints the message: hello, world

## What I learned
- How to write a basic C program
- How to use #include <stdio.h> for input/output
- How to compile code using 'make'
- How to execute a compiled C program

## How to Run It:
1. Open terminal
2. Go to hello.c folder
3. Compile code by typing "make hello"
4. Run the program using "./hello"

## File:
- 'hello.c' : Source code for Hello World program

## 2. Mario (Less)

## What It Does:
This program asks the user to input a height (1-8) and prints a right aligned pyramid just like one on a mario game.

## What I Learned:
- How to prompt a user for input using 'get_int()'
- How to use 'do...while' loops
= How to use 'for loops' nested in each other 

## How to Run:
1. Open Terminal
2. Go to 'mario-less' folder
3. Compile the code by typing "make mario"
4. Run the program with "./mario"
5. Enter a height between 1 and 8

## File:
- 'mario.c' - Source code for Marioless program

## Mario (More)

## What It Does:
This program asks the user to input a height between 1-9 and prints two side by side ppyramids with spaces separating them 

## What I learned:
- How to use 'get_int()' for user input
- How to use 'do...while' loops to validate input
- How to use nested 'for' loops to build each row of the pyramid
- How to print characters and spaces in specific patterns

## How to Run:
1. Open Terminal
2. Go to 'mario-more' folder
3. Compile code by typing "make mario"
4. Run program with "./mario"
5. When promoted, enter a height between 1-8

## File:
- 'mario.c' - Source code for MarioMore Program

## Credit

## What It Does:
This program asks the user for a card number and checks if the card number is valid using Luhn's Algorithm, if it's valid then the card is identified as either Amex, Mastercard, or Visa based on the number's length and starting digits. If no conditions are met, then it prints invalid.

## What I learned:

- How to code Luhn's Algorithm
- Extraction of digits using % and /
- Count digits and track position while looping
- How to use loops and operations to manipulate numbers

## How to Run:
1. Open Terminal
2. Go to credit folder
3. Compile code by typing "make credit"
4. Run programm with "./credit"
5. When prompted, enter a card number to validate

## Scrabble

## What It Does:
This program simulates a two-player Scrabble-like word game. Each player inputs a word and the program calculates a score for each word based on the Scrabble letter values. The player who types the word with the highest score wins or if the score of both of the words are equal, it's declared a tie.

## What I learned

- How to use 'if', 'else if', and 'else' conditionals to control the output of the program
- Loops to check characters in a string
- Calculations of character position using ASCII arithmetic
- Use of functions to organize and reuse code
- Use of arrays to utilize characters at certain indexes

## How to Run:
1. Open Terminal
2. Go to scrabble folder
3. Compile code by typing "make scrabble"
4. Run program with "./scrabble"
5. When prompted, enter a word for player 1 and player 2

## Readability

## What It Does:
This program analyzes a block of text and calculates its reading level using the Coleman-Liau index. It counts the number of letters, words, and sentences in the input, then uses a formula to estimate the grade level required to understand the text.

## What I learned 
- Loops and Conditionals to count characters, words, and sentences
- The use of isalpha, isspace, and punctuation checks for classification
- The application of mathematical formulas using float division and rounding

## How to Run:
1. Open Terminal
2. Go to readability folder
3. Compile code by typing make readability
4. Run program with ./readability
5. When prompted enter a block of text to analyze

## Caesar

## What It Does:
This program encrypts messages using the Caesar cipher - a substitution cipher where each letter in plaintext is shifted by a user-provided key. The user inputs a key as a command line argument, then types a message. The program rotates each alphabetical character by that number of positions in the alphabet, preserving the case and leaving non-alphabetical letters unchanged.

## What I learned
- Command Line Arguments
- Validation of input using custom functions and isdigit
- Conversion of a string input to an integer using atoi
- Rotation of characters using ASCII arithmetic and modulo

## How to Run:
1. Open Terminal
2. Go to caesar folder
3. Compile code by typing make caesar
4. Run program with ./caesar [key]
5. When prompted, enter a message to encrypt

## Substitution

## What It Does:
This program encrypts messages using the substitution cipher - a cipher where each letter in plaintext is replaced with a corresponding letter based on a 26 letter key the user provided. The program preserves the orginal casing of each letter and leaves non-alphabetic letters unchanged

## What I Learned
- Command Line Arguments
- Checking for duplicate characters
- ASCII arithmetic to find the alphabetical index of characters
- Using tolower() and toupper() to preserve case during substitution
- Manipulating string character by character

## How to Run:
1. Open Terminal
2. Go to substitution folder
3. Compile code by typing make substitution
4. Run program with ./substitution [key]
5. When prompted, enter a message to encrypt
