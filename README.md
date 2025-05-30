# coderschool-interview

The following prompts below are sample projects that could be done with students at "TheCoderSchool". The sample prompts below are used to evaluate candidates that want to become code coaches/teach classes. The prompts are provided to evaluate how a candidate will walk through and coach a student through one of the projects below. 

## Rules

1. The interview exercise will simulate picking a project with a student. All 3 prompts will be provided but the candidate will need to help the student choose a project and get then interested in the exercise. 
2. Candidate will need to explain the requirements to the student as the project/solution is being built out. The student will need to have context of each requirement and how the code translates. 
3. The project implementation must be completed in python.
4. It is not foribidden to use the internet for searching documentation/syntax but use of ChatGPT is not allowed for this exercise. The purpose of this is to demonstrate what the candidate can teach a student fluently without relying heavily on external sources. 
5. Completion of the code is less important then explaining the thought process and making sure the student understands the code. It is not required to finish the prompts or the projects. 


# Rock Paper Scissors

This project is a rock paper scissors simulator. This project will be a command line interface project that lets a user play rock paper scissors against a random computer bot. The computer bot will generate 3 random options "rock", "paper" or "scissors" which the user will not be able to see. Then the user will be able to either type in their option and see if they can beat the computer. 

## Game Rules

1. Rock wins against scissors.
2. Scissors win against paper.
3. Paper wins against rock.

## Requirements
 
* The computer will need to randomly select an option "rock", "paper" or "scissors". 
* The user will need to be able to type in an option for either of the 3 options
* The program will then need to do the logic to determine if the computer or the player won

# Blackjack

This project will be a card game simulator for "blackjack". Blackjack is a popular card game for playing against the card dealer. The goal of the game is to draw a random deck of cards that has the closest total to 21. For the sake of simplicity, this project will not require simulating a card deck and will just generate random numbers between 1-10 to simulate drawing a card out of a deck. For this project, the user will play against a random computer that will generate a number between 1-21.

## Requirements
 
* The program will need to be able to generate random numbers between 1-21 and 10-21
* The program will need to store a list to keep track of the number of cards the user has drawn
* The program will need to filter the input of the user based on whether they type "stay" or "hit"
* If the user types "stay" it should draw a random number and add it to the card deck list, if the user types "hit", the user should keep their current cards and then allow the computer bot to draw their cards.
* To determine the winner, the program will need to be able to sum the numbers in the list to see what the user's total hand was to compare it against the computer bot and determine the winner. 


# Calculator

This project will be a command line interface (CLI) calculator that allows the user to perform basic arithmetic operations. The user will be able to input two numbers and an operation (such as addition or division), and the program will output the result. The calculator will support common mathematical operations and provide helpful error messages for invalid input.

## Requirements

- The program must accept user input for:
    - The first number (integer or decimal).
    - The operation (`+`, `-`, `*`, `/`).
    - The second number (integer or decimal).
- The program must perform the selected arithmetic operation and print the result.
- The calculator must support the following operations:
    - Addition (`+`)
    - Subtraction (`-`)
    - Multiplication (`*`)
    - Division (`/`)
- The program must handle invalid input gracefully:
    - Non-numeric values.
    - Division by zero (should display an error and not crash).
    - Invalid operation symbols.
- After each calculation, the user should be prompted to perform another calculation or exit the program.
