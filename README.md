

# Road Crossing Ball 🏐🚧

An **interactive OpenGL game** built with Python's `PyOpenGL` library, where the player controls a ball that must cross multiple lanes filled with moving obstacles. The goal is to reach the top without colliding with obstacles while managing limited lives.



## 📌 Overview

The *Road Crossing Ball* is inspired by classic arcade crossing games but built entirely from scratch using **midpoint circle** and **midpoint line algorithms** for graphics rendering. The player must navigate a ball vertically across lanes of moving obstacles, avoiding collisions, and aiming for the highest score possible.

This project demonstrates:

* Low-level drawing algorithms (midpoint circle & line)
* Object movement and collision detection
* Player input handling (keyboard & mouse)
* Game state management (lives, score, pause/resume, restart)



## 🛠 Features & Functionality

### 🎮 Player Mechanics

* **Movement:** Control the ball with arrow keys to move **up, down, left, right**.
* **Objective:** Reach the top of the screen to score.
* **Lives:** Start with 3 lives; collision with an obstacle removes 1 life.

### 🚧 Obstacles

* Randomly generated horizontal bars that move left or right.
* Bounce back when hitting the screen edges.
* Multiple lanes of obstacles with different speeds.

### 🖥 Controls

| Action         | Input                                 |
| -------------- | ------------------------------------- |
| Move Up        | **Arrow Up**                          |
| Move Down      | **Arrow Down**                        |
| Move Right     | **Arrow Right**                       |
| Move Left      | **Arrow Left**                        |
| Pause / Resume | Click **Pause button** in the top bar |
| Restart Game   | Click **Restart button**              |
| Exit Game      | Click **Exit button**                 |

### 🔄 Game State

* **Pause/Resume** toggle using mouse clicks.
* **Restart** resets position, score, and lives.
* **Game Over** when lives reach zero (ball turns red).



## 📐 Technical Details

* **Graphics Algorithms:**

  * *Midpoint Circle Algorithm* for rendering the ball.
  * *Midpoint Line Algorithm* for rendering obstacles, lanes, and buttons.
* **Language:** Python 3
* **Libraries:** PyOpenGL, random
* **Resolution:** 500×500 pixels orthographic view.



## 🖼 Image Previews


Start:

<img src="https://github.com/JAWAD645/Road-Crossing-Ball-Game/blob/9eab839ddbdf8751f5e1e3c8c272eb60f7784188/RCB_Start.png" alt="Game Screenshot" width="400">

End:

<img src="https://github.com/JAWAD645/Road-Crossing-Ball-Game/blob/9eab839ddbdf8751f5e1e3c8c272eb60f7784188/RCB_End.png" alt="Game Screenshot" width="400">

Play this demo:

<img src="https://github.com/JAWAD645/Road-Crossing-Ball-Game/blob/2ab9e20dcc3a471bd53aff6bad0cc19f1bea5f7e/Overview%20of%20the%20project.gif" alt="Game Screenshot" width="400">


## 📥 Installation & Running

### 1️⃣ Install Python

Ensure **Python 3.8+** is installed.
[Download Python](https://www.python.org/downloads/)

### 2️⃣ Install Required Libraries

```bash
pip install PyOpenGL PyOpenGL_accelerate
```

### 3️⃣ Download the Project

```bash
git clone https://github.com/<your-username>/road-crossing-ball.git
cd road-crossing-ball
```

### 4️⃣ Run the Game

```bash
python "Road Crossing Ball.py"
```

---

## 🏆 Scoring

* +1 point for each upward move.
* Reset position when reaching the top lane successfully.
* Losing a life resets the ball position.



## 🔮 Future Improvements

* Add difficulty levels (increase obstacle speed over time).
* Implement sound effects.
* Add a start menu and better UI.



## 👨‍💻 Author

**Jaawad Tashick**
*Computer Science Graduate *


