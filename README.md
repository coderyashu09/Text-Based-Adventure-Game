# 🕹️ Text-Based Adventure Game (Python)

A simple command-line adventure game built using Python.
The player makes choices at each stage of the story and the game progresses based on those inputs.

---

## 📌 Project Description

This project is a small interactive **text-based adventure game** where:

* The player starts at a forest entrance
* Makes choices such as entering the forest, following a path, entering a cabin, and opening a treasure chest
* The game ends either with a **win** or a **game over**

The full game flow and explanation is described in the project notes .

---

## 📂 Project Files

* `main.py` – main game program 
* `explanation.txt` – explanation of game logic and flow 

---

## ⚙️ Requirements

* Python 3.x
* No external libraries required
  (only built-in Python features are used) 

---

## ▶️ How to Run the Game

```bash
python main.py
```

---

## 🎮 How the Game Works

* The game starts with an introduction
* The player types choices such as:

  * `enter`, `leave`
  * `follow`, `turn back`
  * `enter`, `continue`
  * `open`, `leave`
* Based on the choice, the story moves to the next stage
* Wrong or exit choices end the game with **Game Over**
* Opening the chest ends the game with a **win** 

---

## 🧠 Game Flow (Logic)

* Each stage of the story is implemented as a **separate function**
* User input is taken using `input()`
* The program uses **if–else conditions** to control the story path
* The `main()` function controls the complete game flow 

---

## ✨ Features

* Simple and beginner-friendly
* Interactive command-line input
* Multiple story paths
* Clear win and game-over ending
* Demonstrates:

  * functions
  * conditional statements
  * user input handling 

---

## 🎯 Learning Purpose

This project is suitable for beginners to understand:

* Function based program structure
* Conditional branching
* Basic program flow control
* Interactive console programs

---

## 🧑‍💻 Author

Yash Kanzariya
AI & ML / Python Student

---
