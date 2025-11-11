🪨 Rock Paper Scissors Game

A simple Rock, Paper, Scissors game written in Python.
Play against the computer and see who wins!

🎮 Features

Play a quick match against the computer

Random computer choice each round

Simple command-line interface

Beginner-friendly Python code

🧠 How to Play

Run the program.

Enter your choice: rock, paper, or scissors.

The computer will randomly choose one.

The result will be displayed instantly — win, lose, or tie!

🧩 Code Example
import random

choices = ["rock", "paper", "scissors"]
computer = random.choice(choices)
player = input("Enter rock, paper, or scissors: ").lower()

print(f"Computer chose: {computer}")

if player == computer:
    print("It's a tie!")
elif (player == "rock" and computer == "scissors") or \
     (player == "paper" and computer == "rock") or \
     (player == "scissors" and computer == "paper"):
    print("You win!")
else:
    print("You lose!")# Rockpaperscissor
