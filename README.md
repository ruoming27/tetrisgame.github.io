
# Tetris Game 🎮

A classic Tetris game implemented in JavaScript and rendered on HTML5 Canvas.

---

## Demo

Play the game live here:  
[https://ruoming27.github.io/tetrisgame.github.io/](https://ruoming27.github.io/tetrisgame.github.io/)

---

## Features

- Classic Tetris gameplay with 7 Tetromino shapes (I, L, J, O, T, S, Z)
- Smooth piece movement and rotation
- Line clearing when a row is full
- Collision detection with arena boundaries and stacked pieces
- Basic wall kick logic for rotations near edges
- Keyboard controls for moving and rotating pieces
- Scalable canvas rendering with simple CSS styling

---

## Controls

| Key          | Action           |
|--------------|------------------|
| Left Arrow   | Move piece left  |
| Right Arrow  | Move piece right |
| Down Arrow   | Soft drop        |
| Q            | Rotate piece CCW |
| W            | Rotate piece CW  |

---

## How to Run Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/ruoming27/tetrisgame.github.io.git
    ```
2. Open `index.html` in your web browser.

---

## Project Structure
tetrisgame.github.io/\
├── index.html # Main HTML file with canvas\
├── style.css # CSS styles for centering and styling\
├── tetris.js # JavaScript game logic\
└── README.md # This file
