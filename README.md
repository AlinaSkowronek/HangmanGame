# Hangman Game

A simple implementation of the classic Hangman word-guessing game.  
The player tries to guess a hidden word one letter at a time before running out of lives.

---

## 🎯 Overview

This project recreates the traditional Hangman game you might play on paper, but in a digital form.  
It’s designed as a small programming project to practice:

- Control flow and game loops
- String / character handling
- Basic input/output
- Simple game state management

---

## 🕹 Features

- Randomly selected secret word from a word list
- Display of:
  - Correctly guessed letters
  - Blanks for unknown letters
  - Letters already guessed
- Limited number of lives/attempts
- Win/Lose detection with final message
- Input validation (ignores repeated/invalid guesses where applicable)

---

## 📖 How to Play

1. The program chooses a secret word.
2. You see the word as a series of underscores, e.g. `_ _ _ _ _`.
3. Type a letter to guess.
4. If the letter is in the word:
   - All positions of that letter are revealed.
5. If the letter is **not** in the word:
   - You lose one life.
6. The game ends when:
   - You correctly guess all letters (🎉 you win), or
   - You run out of lives (💀 you lose).

---


