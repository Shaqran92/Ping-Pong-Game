# 🏓 Ping Pong Game – Python Turtle Project

A classic Ping Pong (Pong) game built entirely using **Python Turtle Graphics**.  
This project recreates the retro arcade experience with smooth controls, dynamic ball speed, collision physics, score tracking, pause/restart options, and a clean UI.

---

## 🚀 Features

### 🎮 Gameplay  
- Two-player controls (W/S for Left, Up/Down for Right)  
- Smooth ball movement  
- Dynamic ball speed that increases after paddle hits  
- Accurate collision detection with paddles and walls  
- First to **5 points** wins  

### 🛠 Game Mechanics  
- Center dashed line for visual appeal  
- Paddle boundary limits  
- Ball speed-level system  
- Auto ball reset after score  
- Fully functional scoreboard  
- In-game messages: *Pause, Restart, Winner messages*

### 🎚 Controls  
| Action | Key |
|-------|------|
| Move Left Paddle Up | **W** |
| Move Left Paddle Down | **S** |
| Move Right Paddle Up | **Up Arrow** |
| Move Right Paddle Down | **Down Arrow** |
| Pause / Resume | **Space** |
| Restart | **R** |
| Quit | **Esc** |

---

## 📁 Project Structure

  📦 PingPongGame
  ├── main.py
  ├── ball.py
  ├── paddles.py
  └── scoreboard.py



---

## 🧩 How It Works

### ⚪ Ball  
- Moves continuously  
- Bounces on walls  
- Reverses direction on paddle collision  
- Speed increases up to a limit  
- Resets after a point is scored

### 🟦 Paddles  
- Move vertically with boundary checks  
- Designed using Turtle shapes  
- Reset on game restart

### 🧮 Scoreboard  
- Tracks left & right player scores  
- Displays instructions  
- Shows winner message  
- Supports reset & pause display

---

## ▶️ Run the Game

Make sure you have **Python 3.x** installed.

```bash
python main.py

