# 🔢 Number Guessing Game (Python)

A simple console-based **Number Guessing Game** written in Python.  
The player must guess a randomly generated number between **1 and 100**, with a limited number of attempts depending on the selected difficulty level.

---

## 📌 How the Game Works

1. The program randomly selects a number between 1 and 100.
2. The player chooses a difficulty level:
   - `easy` → 10 attempts
   - `hard` → 5 attempts
3. The player makes guesses.
4. After each guess, the game provides feedback:
   - Too high
   - Too low
5. The game ends when:
   - The player guesses correctly ✅
   - The player runs out of attempts ❌

---

## 🧠 Features

- Two difficulty levels (easy / hard)
- Random number generation
- Feedback after every guess
- Attempt tracking
- Clean function-based design

---

## 📂 Project Structure

```
number-guessing-game/
│
├── main.py
└── README.md
```

---

## 🛠️ Technologies Used

- Python 3
- random module

---

## ▶️ How to Run the Game

1. Make sure **Python 3** is installed.
2. Save the script as `main.py`.
3. Run the program from the terminal:

```bash
python main.py
```

4. Follow the prompts to play the game.

---

## 🎮 Example Gameplay

```
Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100.
Choose a difficulty. Type 'easy' or 'hard': easy
You have 10 attempts remaining to guess the number.
Make a guess: 50
Too low.
Guess again.
```

---

## 🎯 Purpose of the Project

This project was created to:
- Practice Python functions and loops
- Understand conditional logic
- Work with random number generation
- Build interactive console programs

---

## 🚀 Possible Improvements

- Remove debug output showing the answer
- Add input validation
- Allow replay without restarting the program
- Add a scoring system
