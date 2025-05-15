# 🐍 Serpent Saga Game Repository

Welcome to the **Serpent Saga** repository — a modern twist on the classic Snake game, fully implemented in **C++** using the **SFML (Simple and Fast Multimedia Library)** for graphical rendering and event handling. This project showcases an interactive arcade game built with **object-oriented programming principles**, clean architecture, and real-time input response.

---

## 🎮 Overview

**Serpent Saga** is a grid-based, real-time arcade game where players control a snake to collect fruits, avoid collisions with bombs and itself, and chase high scores. The game introduces increasingly challenging elements such as dynamically spawning bombs and growing snake length, offering a balance of strategy, reflexes, and fun.

This project is designed to reinforce key **C++ OOP concepts** like:

- **Encapsulation**: Snake behavior, game state, and rendering logic are separated into dedicated classes.
- **Inheritance**: Game objects such as fruits and bombs share common interfaces.
- **Polymorphism**: Used for rendering and event-driven updates of different game entities.
- **Abstraction**: High-level game logic is abstracted behind simplified interfaces.
- **Composition & Aggregation**: The game scene is composed of multiple objects that interact and update based on the game loop.
- **File I/O**: High score tracking using file persistence.

---

## 🧩 Features

### 🎯 Core Gameplay
- Classic snake mechanics: move, grow, and avoid collisions
- Fruit collection to increase score and snake length
- Randomized bomb placement for added difficulty

### 🕹️ Intuitive Controls
- Arrow keys to control the snake
- `P` to pause/resume
- `R` to restart the game instantly

### 📊 Real-Time Score Tracking
- Live score display during gameplay
- Highest score saved between sessions

### 🧵 Smooth SFML-Powered Graphics
- Animated movement and transitions using SFML
- Clean and responsive visual layout

---

## 🔧 How to Build and Run

### 🔃 Clone the Repository

```bash
git clone https://github.com/yourusername/serpent-saga.git
cd serpent-saga
