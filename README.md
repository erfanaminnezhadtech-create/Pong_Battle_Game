# 🏓 Canvas Pong Game

A simple **Pong** game built with **vanilla JavaScript** and **HTML5 Canvas** where the player competes against the computer. This project is implemented without any external libraries and is perfect for learning basic Canvas concepts, animation, and game logic.

---

## 🎮 Features

* Graphics rendered with HTML5 Canvas
* Player paddle controlled with mouse movement
* Simple AI for the computer paddle
* Different speed settings for mobile and desktop
* Scoring system
* Game Over screen with replay option
* Gradual increase in ball speed

---

## 🛠️ Technologies Used

* JavaScript (Vanilla)
* HTML5 Canvas API
* Minimal CSS (for Game Over screen)

---

## 📂 Project Structure

```text
project/
│
├── index.html
├── script.js   // Main game logic
└── README.md
```

> The provided code corresponds to `script.js`.

---

## 🚀 How to Run

1. Create an `index.html` file
2. Put the JavaScript code in `script.js`
3. Link the JS file to the HTML
4. Open `index.html` in your browser

### Sample HTML:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Canvas Pong Game</title>
  <style>
    body {
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #111;
    }
  </style>
</head>
<body>
  <script src="script.js"></script>
</body>
</html>
```

---

## 🕹️ How to Play

* The bottom paddle belongs to the player
* **Move your mouse** to control the paddle
* Bounce the ball back toward the computer paddle
* The first to reach **7 points** wins

---

## ⚙️ Game Logic (Summary)

### 🎾 Ball

* Moves vertically and horizontally
* Speed increases after hitting a paddle
* Direction changes based on where it hits the paddle

### 🧠 Computer AI

* Follows the ball's X position
* Speeds up as the game progresses

### 📱 Mobile Support

```js
if (isMobile.matches) {
  speedY = -2;
  speedX = speedY;
  computerSpeed = 4;
}
```

---

## 🔁 Game Over

* Triggers when a player reaches 7 points
* Displays the winner
* **Play Again** button to restart the game

---

## ✨ Ideas for Improvement

* Add sound effects
* Touch support for mobile
* Two-player mode
* Difficulty selection
* Enhanced UI and animations

---

## 📜 License

This project is free to use for learning, practice, or personal development.

---

### 👨‍💻 Made for learning and practicing Canvas and game logic
