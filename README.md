# 🏓 Pong Game (Pygame)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)

---

## 👤 Author
Ben Stearns - [@bstearns07](https://github.com/bstearns07)

📅 **Last Updated:** 6/1/2024

---

## 📑 Table of Contents
- 📌 [Summary](#-summary)
- ⭐ [How It Works](#-how-it-works)
- ✨ [Features](#-features)
- 🧰 [Tech Stack](#-tech-stack)
- 🔧 [Development Tools](#-development-tools)
- 🧩 [Core Concepts](#-core-concepts)
- 📝 [New Topics Covered](#-new-topics-covered)
- 📝 [What I Learned](#-what-i-learned)
- ▶️ [How to Run](#-how-to-run)
- 🖼 [Screenshot](#-screenshot)

---

## 📌 Summary

This project is a fully functional recreation of the classic **Pong arcade game**, built using Python and the Pygame library.

Players control paddles on opposite sides of the screen and compete to score points by getting the ball past their opponent. The game includes collision physics, score tracking, and win conditions.

---

## ⭐ How It Works

- Two players control paddles:
  - **Left Player:** `W / S`
  - **Right Player:** `↑ / ↓`
- The ball moves across the screen and bounces off:
  - Top and bottom walls
  - Player paddles
- Each time the ball passes a paddle, the opposing player scores
- First player to reach **10 points wins**
- Game resets after displaying the winner

---

### ▶️ How to Run

1. Install Pygame:
   ```bash
   pip install pygame

---

## ✨ Features

- 🎮 Two-player local gameplay
- 🧠 Dynamic ball physics (angle changes based on paddle hit location)
- 📊 Real-time score tracking
- 🔁 Automatic game reset after win
- 🎯 Collision detection (walls + paddles)
- ⚡ Smooth 60 FPS gameplay loop

---

## 🧰 Tech Stack

- 🐍 Python
- 🎮 Pygame

---

## 🔧 Development Tools

- Pycharm IDE

---

## 🧩 Core Concepts

- Object-Oriented Programming (Paddle & Ball classes)
- Game loop architecture
- Event handling (keyboard + window events)
- Collision detection and response
- Velocity and vector-based movement
- Rendering graphics with Pygame

---

## 📝 New Topics Covered

- Using Pygame to create a game in python
- Using pypi website to search for libraries
- More advanced math functions for calculating speed/velocity of an object

---

## 📝 What I Learned

- How to structure a real-time game loop
- Managing frame rate with `pygame.time.Clock`
- Handling user input for multiple players
- Implementing physics-based interactions
- Breaking logic into reusable classes and functions

---

## 🖼 Screenshots

![Game Playing](assets/pong.png)
